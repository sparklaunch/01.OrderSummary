<div id="plan">
  <div id="plan-icon">
    <img src="/assets/icon-music.svg" alt="Music Icon" />
  </div>
  <div id="plan-text">
    <p>Annual Plan</p>
    <p>$59.99/year</p>
  </div>
  <div id="plan-change">
    <p>Change</p>
  </div>
</div>

<style>
  #plan {
    background-color: rgb(246, 246, 255);
    border-radius: 10px;
    margin: auto;
    width: 300px;
    display: flex;
    align-items: center;
  }
  #plan-icon {
    flex-grow: 0;
    flex-shrink: 0;
    padding: 20px;
  }
  #plan-text {
    font-family: "Outfit", sans-serif;
    flex-grow: 1;
  }
  #plan-text > p:first-child {
    color: rgb(27, 34, 61);
    font-weight: 600;
    margin-bottom: 5px;
  }
  #plan-text > p:last-child {
    color: rgb(108, 113, 132);
  }
  #plan-change {
    flex-grow: 0;
    flex-shrink: 0;
    font-family: "Outfit", sans-serif;
    padding: 20px;
  }
  #plan-change > p {
    cursor: pointer;
    color: blue;
    text-decoration: underline;
    font-weight: 600;
    transition: color 0.3s;
  }
  #plan-change > p:hover {
    color: rgb(139, 131, 227);
  }
</style>
