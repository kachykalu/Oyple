# Oyple
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Oyple</title>
    <link rel="stylesheet" href="../src/style.css" />
  </head>
  <body>
    <div class="container">
      <header>
        <img
          style="width: 72px; height: 24.988px"
          src="../assets/Logo-white.png"
          alt=""
        />

        <img src="../assets/menu.svg" alt="" />
      </header>
      <section class="navBar">
        <div>
          <img
            style="margin-left: 27px; margin-top: 34.5px"
            src="../assets/Logo-white.png"
          />
          <div>
            <span
              class="onClick"
              style="
                display: flex;
                flex-direction: row;
                align-items: center;
                padding: 20px 16px;
                gap: 8px;
                margin-top: 18.57px;
              "
            >
              <img src="../assets/home-2.svg" alt="" />
              <p style="font-size: 14px">Home</p>
            </span>
            <span
              style="
                display: flex;
                flex-direction: row;
                align-items: center;
                padding: 20px 16px;
                gap: 8px;
              "
            >
              <img src="../assets/calendar-tick.svg" alt="" />
              <p style="font-size: 14px">My events</p>
            </span>
            <span
              style="
                display: flex;
                flex-direction: row;
                align-items: center;
                padding: 20px 16px;
                gap: 8px;
              "
            >
              <img src="../assets/note.svg" alt="" />
              <p style="font-size: 14px">Order</p>
            </span>
            <span
              style="
                display: flex;
                flex-direction: row;
                align-items: center;
                padding: 20px 16px;
                gap: 8px;
              "
            >
              <img src="../assets/wallet-2.svg" alt="" />
              <p style="font-size: 14px">Wallet</p>
            </span>
            <span
              style="
                display: flex;
                flex-direction: row;
                align-items: center;
                padding: 20px 16px;
                gap: 8px;
              "
            >
              <img src="../assets/setting-2.svg" alt="" />
              <p style="font-size: 14px">Settings</p>
            </span>
          </div>
        </div>
        <div style="margin-bottom: 24px">
          <div
            style="display: flex; justify-content: space-between; padding: 12px"
          >
            <div
              style="
                display: flex;
                flex-direction: row;
                align-items: center;
                gap: 8px;
              "
            >
              <img
                class="profileAvatar"
                src="../assets/Avatar.png"
                style="width: 32px; height: 32px"
                alt=""
              />
              <span
                class="username-email"
                style="display: flex; flex-direction: column"
              >
                <p style="font-size: 14px">Olivia Rhye</p>
                <p style="font-size: 12px">oli@gmail.com.com</p>
              </span>
            </div>
            <img class="logout1" src="../assets/logout.svg" alt="" />
          </div>
        </div>
      </section>
      <section id="hello-jane">
        <div
          style="
            padding: 32px 32px 25px 32px;
            display: flex;
            flex-direction: column;
            gap: 25px;
            border: 1px solid var(--greyBlue);
            background-color: var(--greyBlue);
          "
        >
          <div
            style="
              display: flex;
              flex-direction: row;
              justify-content: space-between;
              width: 100%;
            "
          >
            <span style="display: flex; flex-direction: column; gap: 8px">
              <h2>Hello, Jane</h2>
              <p>Thursday, February 14</p>
            </span>
            <span
              style="
                border-radius: 12px;
                border: 1px solid #555a57;
                background: linear-gradient(
                    180deg,
                    rgba(255, 255, 255, 0.1) 0%,
                    rgba(165, 238, 238, 0) 100%
                  ),
                  #1e2320;
                box-shadow: 0px 0px 0px 1px #1e2320;
                display: flex;
                padding: 8px 16px;
                align-items: center;
                color: white;
              "
            >
              <p>Get Started</p></span
            >
          </div>
          <div id="net-items">
            <span id="net-sales">
              <p style="font-size: 14px">Net Sales</p>
              <h3 style="font-size: 32px">₦47,000.00</h3>
            </span>
            <span
              style="
                display: flex;
                flex-direction: column;
                gap: 9px;
                padding: 16px;
                border-radius: 12px;
                width: 100%;
                border: 1px solid #eee;
                background: white;
              "
            >
              <p style="font-size: 14px">Items bought</p>
              <h3 style="font-size: 32px">35</h3>
            </span>
          </div>
          <div style="position: relative">
            <span
              style="
                position: absolute;
                right: 0;
                display: flex;
                flex-direction: row;
                align-items: center;
                gap: 8px;
                color: #5e779d;
              "
            >
              <p style="font-size: 14px">Get paid</p>
              <img src="../assets/arrow-up.svg" alt="" />
            </span>
          </div>
        </div>
        <div
          style="
            margin: 40px 32px 20px 32px;
            display: flex;
            flex-direction: column;
            gap: 20px;
          "
        >
          <div
            style="
              display: flex;
              flex-direction: row;
              justify-content: space-between;
            "
          >
            <p style="font-size: 18px">Recently paid</p>
            <p style="font-size: 14px">View all</p>
          </div>
          <table class="reusable-table">
            <tr>
              <td>Transaction ID</td>
              <td>Name</td>
              <td>Email</td>
              <td>Phone</td>
              <td>Quantity</td>
              <td>Price</td>
              <td>Date</td>
            </tr>
            <tr>
              <th>0034</th>
              <th>John Adekunle</th>
              <th>john@gmail.com</th>
              <th>+2349085763625</th>
              <th>3</th>
              <th>₦4,500.00</th>
              <th>1/11/24</th>
            </tr>
            <tr>
              <th>0034</th>
              <th>John Adekunle</th>
              <th>john@gmail.com</th>
              <th>+2349085763625</th>
              <th>3</th>
              <th>₦4,500.00</th>
              <th>1/11/24</th>
            </tr>
            <tr>
              <th>0034</th>
              <th>John Adekunle</th>
              <th>john@gmail.com</th>
              <th>+2349085763625</th>
              <th>3</th>
              <th>₦4,500.00</th>
              <th>1/11/24</th>
            </tr>
            <tr>
              <th>0034</th>
              <th>John Adekunle</th>
              <th>john@gmail.com</th>
              <th>+2349085763625</th>
              <th>3</th>
              <th>₦4,500.00</th>
              <th>1/11/24</th>
            </tr>
            <tr>
              <th>0034</th>
              <th>John Adekunle</th>
              <th>john@gmail.com</th>
              <th>+2349085763625</th>
              <th>3</th>
              <th>₦4,500.00</th>
              <th>1/11/24</th>
            </tr>
            <tr>
              <th>0034</th>
              <th>John Adekunle</th>
              <th>john@gmail.com</th>
              <th>+2349085763625</th>
              <th>3</th>
              <th>₦4,500.00</th>
              <th>1/11/24</th>
            </tr>
            <tr>
              <th>0034</th>
              <th>John Adekunle</th>
              <th>john@gmail.com</th>
              <th>+2349085763625</th>
              <th>3</th>
              <th>₦4,500.00</th>
              <th>1/11/24</th>
            </tr>
          </table>
        </div>
        <div id="history">
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
          <div class="recently-paid">
            <span class="recently-paid-name">
              <p style="font-size: 14px">John Adekunle</p>
              <span id="details"
                >0034 <span class="dot"></span>25/07/24, 10:35:56</span
              >
            </span>
            <p style="font-size: 14px">₦4,500.00</p>
          </div>
        </div>
      </section>
    </div>
  </body>
</html>
