<div id="buttons">
  <button id="proceed">Proceed to Payment</button>
  <button id="cancel">Cancel Order</button>
</div>

<style>
  #buttons {
    display: flex;
    flex-direction: column;
    width: 300px;
    margin: 30px auto;
  }
  #proceed {
    border: none;
    border-radius: 10px;
    font-family: "Outfit", sans-serif;
    font-weight: 600;
    background-color: rgb(49, 37, 221);
    color: white;
    font-size: 18px;
    padding: 15px 0;
    box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.5);
    margin-bottom: 20px;
    cursor: pointer;
  }
  #cancel {
    border: none;
    border-radius: 10px;
    font-family: "Outfit", sans-serif;
    font-weight: 600;
    color: rgb(108, 114, 143);
    background-color: transparent;
    font-size: 18px;
    padding: 10px 0;
    cursor: pointer;
  }
</style>
