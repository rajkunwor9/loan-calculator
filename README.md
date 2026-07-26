# Loan Repayment Calculator

A fully interactive, browser‑based tool to compare standard repayments against accelerated strategies – including regular extra payments and annual lump‑sum contributions. Adjust sliders, switch repayment frequencies, and see instant feedback on interest saved and time shaved off your mortgage.
<img width="795" height="823" alt="image" src="https://github.com/user-attachments/assets/6d1ffde7-d30b-49c1-aab6-1bea0200dfcd" />

## 🔍 Why This Calculator?

Most loan calculators only show the monthly payment. This one goes further by modelling **two powerful strategies**:

- **Regular extra payments** – e.g. adding $100 per fortnight to your minimum repayment.
- **Annual lump sums** – a one‑off payment once a year (e.g. a tax refund or bonus) that goes straight to principal.

The tool visualises how these extra contributions compound over time, reducing both total interest and the loan term.

## ✨ Key Features

- **Real‑time sliders** – adjust principal, term, and interest rate; all results update instantly.
- **Frequency toggle** – switch between **Fortnightly** and **Monthly** schedules (defaults: $300/fortnight, $500/month extra).
- **Annual lump‑sum slider** – model a yearly bonus; the *“Use monthly EMI”* button sets the lump sum to exactly one standard monthly repayment.
- **Side‑by‑side comparison** – regular vs extra repayment summary, including interest / principal ratios.
- **Amortisation charts** – balance‑over‑time line chart and a bar chart comparing principal, interest, and total paid.
- **Instant savings metrics** – displays total interest saved and time saved at a glance.
- **Educational notes** – explains the mechanics and highlights the importance of consistency.

## 🖥️ How to Use

1.  Adjust the **Principal**, **Loan Term**, and **Interest Rate** to match your loan.
2.  Select your preferred **Repayment Frequency**.
3.  Set a regular **Extra Payment** (per period) and/or an **Annual Lump Sum**.
4.  Watch the summary, charts, and savings update automatically.
5.  visit to https://rajkunwor9.github.io/loan-calculator/

## ⚙️ Technical Stack

- **HTML5** – semantic structure.
- **CSS3** – custom properties (variables) for theming; fully responsive grid layout.
- **Vanilla JavaScript** – no external libraries. All calculations (EMI, amortisation with lump sums) and canvas‑based charts are written from scratch.

## 🚀 Getting Started (Local Use)

Download the `index.html` file and open it in any modern web browser. No server or internet connection required (except for loading Google Fonts on the first visit).

```bash
# Clone this repository
git clone https://github.com/rajkunwor9/loan-calculator.git

# Or just download the index.html directly
