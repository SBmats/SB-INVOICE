<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>SB Billing System</title>
  </head>
  <body>
    <div class="form-section">
      <h2>Billing Form</h2>

      <div class="form-group">
        <label>Customer Name:</label>
        <input type="text" id="customerName" />
      </div>
      <div class="form-group">
        <label>Mobile Number:</label>
        <input type="text" id="customerMobile" />
      </div>

      <h3>Add Product</h3>
      <div class="form-group">
        <label>Height (fits):</label>
        <input type="number" id="height" />
      </div>
      <div class="form-group">
        <label>Width (fits):</label>
        <input type="number" id="width" />
      </div>
      <div class="form-group">
        <label>Price per Fit (₹):</label>
        <input type="number" id="pricePerFit" />
      </div>

      <button onclick="addItem()">Add Item</button>
      <button onclick="generateBill()">Generate Bill</button>
    </div>

    <div class="bill-section" id="bill">
      <h2>SBmats.com</h2>
      <h4>K VENKATESWARA RAO</h4>
      <h4>+91 9346304276,+91 9441982385</h4>
      <h4>Pallakollu Read Narasapuram</h4>

      
      <hr />
      <div class="bill-content">
        <p id="billName"></p>
        <p id="billMobile"></p>
        <hr />
        <div id="itemsList"></div>
        <hr />
        <p id="grandTotal"></p>
        <p style="text-align: center">Total Amount Paid Thank You!</p>
      </div>
    </div>

  </body>
</html>
