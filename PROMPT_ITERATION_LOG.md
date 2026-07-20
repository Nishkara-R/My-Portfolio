content = """#  Prompt Iteration Log & Cross-Model Audit

##  Target Task (FL-01 Audit)
**Task:** Build a production-ready, client-side dynamic invoice generator component that automatically handles line-item calculations, tax rates, input validation, and print styling without external libraries.

---

## 0. Naive Baseline (Pre-Track Version)

###  Prompt
> "Write code for an invoice generator web page."

###  Output (Excerpt)
```html
<!DOCTYPE html>
<html>
<head><title>Invoice</title></head>
<body>
  <h1>Invoice Generator</h1>
  <form>
    <label>Item Name:</label> <input type="text"><br>
    <label>Price:</label> <input type="number"><br>
    <button type="submit">Generate</button>
  </form>
</body>
</html>