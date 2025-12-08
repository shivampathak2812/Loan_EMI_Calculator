# **Loan EMI Calculator (Python Project)**
A simple and modular Loan EMI Calculator built using Python.
This project calculates the EMI (Equated Monthly Installment), generates a full payment schedule, and plots an EMI chart using Matplotlib.

---

## **Features**
1. Calculate EMI based on loan amount, interest rate, and tenure  
2. Generate complete amortization schedule  
3. Plot EMI chart (Principal vs Interest breakup)  
4. Clean modular Python code (main.py, calculator.py, chart.py)

---

## **Project Structure**
LoanCalculator/
│
├── main.ipynb         # Entry point of the program  
├── calculator.ipynb   # EMI calculation + schedule generation  
└── chart.ipynb        # Chart plot using Matplotlib

---

## **How It Works**
1. User enters:  
   - Loan Amount  
   - Annual Interest Rate (%)  
   - Tenure (Years)

2. Program outputs:  
   - Monthly EMI  
   - Total payment  
   - Total interest  
   - Amortization schedule  
   - Chart of EMI breakup

---

## **Setup Instructions**

### **1. Install Python packages**
pip install matplotlib

### **2. Run the project**
python main.py

---

## **Sample Code Overview**

### **main.py**
- Takes user input  
- Calls EMI calculator  
- Displays EMI  
- Shows schedule  
- Calls chart function  

### **calculator.py**
- calculate_emi()  
- generate_schedule()  

### **chart.py**
- plot_emi_chart() using Matplotlib  

---

## **Future Enhancements**
- Add FastAPI backend  
- Build UI using React  
- Add CSV/PDF export  
- Add web-based version

---

## **License**
Free to use and modify for learning.
