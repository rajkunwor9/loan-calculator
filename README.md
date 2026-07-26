# loan-calculator
Visual loan repayment calculator comparing standard vs. extra payment strategies. Features amortization charts, interest savings, and payoff timelines. Educational use only.# Loan Repayment Calculator

A fully interactive, browser-based tool that helps you visualize the long-term impact of making extra repayments on your loan. Adjust the sliders, switch repayment frequencies, and see instant feedback on how much interest you can save and how quickly you can become debt-free.

![Screenshot of Loan Calculator](https://via.placeholder.com/800x400?text=Loan+Repayment+Calculator+Preview)

## 🔍 Why This Calculator?
Most loan calculators only tell you your monthly payment. This tool goes further by showing you the **power of extra repayments**. Every extra dollar you pay reduces the principal, which stops future interest from accruing on that amount. Over time, this compounding effect can save you thousands and shave years off your loan term.

## ✨ Key Features
- **Dynamic Input Sliders** – Adjust loan principal, interest rate, and loan term in real-time.
- **Repayment Frequency** – Toggle between **Fortnightly** (26 payments/year) and **Monthly** (12 payments/year) to match your actual repayment schedule.
- **Extra Payment Simulator** – Set your extra contribution (defaults to **$300/fortnight** or **$500/month**) and watch the numbers change.
- **Side-by-Side Comparison** – See a clear breakdown of regular vs. accelerated repayments, including total interest, total payment, and new payoff term.
- **Amortization Chart** – Visualize the loan balance declining over time for both scenarios.
- **Principal vs. Interest Pie Charts** – Understand exactly how much of your total payment goes toward interest versus the actual loan balance.
- **Instant Savings Metrics** – Displays total interest saved and total time saved at a glance.

## 🖥️ How to Use
1.  Adjust the **Principal**, **Loan Term**, and **Interest Rate** sliders to match your loan details.
2.  Select your preferred **Repayment Frequency** (Fortnightly or Monthly).
3.  Use the **Extra Payment** slider to add a fixed amount to each regular repayment.
4.  Instantly view the updated summary, charts, and savings metrics on the same page.

## ⚙️ Technical Stack
- **HTML5** – Semantic structure.
- **CSS3** – Custom properties (CSS variables) for theming, fully responsive grid layout.
- **Vanilla JavaScript** – No external libraries required. All calculations (amortization, EMI, compounding) and visualizations (Canvas API) are built from scratch.

## 🚀 Getting Started (Local Use)
Simply download the `index.html` file and open it in any modern web browser. No servers, installations, or internet connection are required (except for loading Google Fonts on the first visit).

```bash
# Clone this repository (if you have Git)
git clone https://github.com/your-username/loan-calculator.git

# Or just download the index.html directly


