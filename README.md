# 🧪 Restful Booker - JMeter Performance & Stress Testing

This project demonstrates performance and stress testing on the [Restful Booker API](https://restful-booker.herokuapp.com) using **Apache JMeter**. It includes simulation of real-world traffic: login, create a booking, and search for a booking, along with timed execution and report generation.

---

## ✅ What Has Been Done

* Designed a JMeter test plan (`booking.jmx`) that simulates:

  * User login
  * Booking creation with random data
  * Booking search using extracted booking ID
* Applied a **Gaussian Random Timer** (Deviation: 2000ms, Constant Delay: 500ms) for realistic traffic simulation
* Performed Load Testing in 3 steps:

  * Step 1: 5 minutes
  * Step 2: 10 minutes
  * Step 3: 15 minutes
* Performed Stress Testing by gradually increasing users until bottlenecks were observed
* Collected test results in `.jtl` format and generated:

  * 📊 HTML reports
  * 📈 Excel summary: [booking-api-test-report.xlsx](https://docs.google.com/spreadsheets/d/1kwt1heUuz7pz7DYWBU7ZNJNcsrNHcVRZ9IavQcZHymI/edit?usp=sharing)

---

## 🔧 Prerequisites

* JMeter 5.5 or later
* Java 8 or higher
* Git (for cloning the repo)

---

## 🚀 How to Run the Test

```bash
# Step 1: Clone the repo
git clone https://github.com/your-username/RestfulBooker_Jmeter_Testing.git
cd RestfulBooker_Jmeter_Testing

# Step 2: Open booking.jmx in JMeter

# Step 3: Run the test (GUI or CLI mode)
# For GUI: Open booking.jmx in JMeter and press Start
# For CLI: jmeter -n -t booking.jmx -l booking.jtl

# Step 4: Generate HTML report
jmeter -g booking.jtl -o Reports/

```
---

## 📷 Screenshots

## 📈 Load Test (Excel Report):
<img width="1367" height="642" alt="load_test" src="https://github.com/user-attachments/assets/1679de2b-f7ba-4651-a122-9c839a4a80e5" />



## 📈 Load Test (HTML Report):
### Step1: 5_Min
<img width="1367" height="1052" alt="4" src="https://github.com/user-attachments/assets/d8caced5-f401-469c-ad4c-b075b3d10179" />

### Step2: 10_Min
<img width="1367" height="1166" alt="2" src="https://github.com/user-attachments/assets/0fc37280-0bd3-4b5d-b8fa-c3540214816e" />

### Step3: 15_Min
<img width="1367" height="1166" alt="3" src="https://github.com/user-attachments/assets/d518a4cb-d2bd-45c0-bf18-84df0562eef0" />

---

## 📉 Stress Test (Excel Report):
<img width="1367" height="642" alt="stress test" src="https://github.com/user-attachments/assets/1e714714-8766-4a37-ba61-accbea966d20" />



## 📉 Stress Test (HTML Report):
### Iteration 2
<img width="1367" height="1052" alt="bKvdM" src="https://github.com/user-attachments/assets/bfa19a4c-5cba-44ff-8137-d8e1b6938b67" />

### Iteration 3
<img width="1367" height="1127" alt="bKvdM" src="https://github.com/user-attachments/assets/2ecdb3aa-1d92-45ad-bace-31b3abfc5dc3" />

### Iteration 3.1
<img width="1367" height="1127" alt="bKv6r" src="https://github.com/user-attachments/assets/544b1cb6-ee3a-4e02-92a0-55986bd3001b" />

### Iteration 3.2
<img width="1367" height="1180" alt="image" src="https://github.com/user-attachments/assets/712112fc-c4a1-409c-b7b7-807b2701abe0" />

### Iteration 3.2.1
<img width="1367" height="1180" alt="image" src="https://github.com/user-attachments/assets/16e7df2c-2825-430b-851f-145dcd128532" />

### Iteration 3.2.2


---

## 👤 Author

**Mohammad Arefin Hossain**
🔗 [LinkedIn](https://www.linkedin.com/in/arefin-hossain/)
✉️ [Email](mailto:arefinstudent71@gmail.com)


---

## ⭐ Final Notes

This project highlights core strengths in:

- ✅ Designing and executing realistic performance test scenarios    
- 📊 Analyzing test metrics (throughput, response time, error rate)  
- 🛠️ Identifying system bottlenecks under varying load conditions  
- 🧪 Applying best practices in software quality assurance and JMeter usage  

---



