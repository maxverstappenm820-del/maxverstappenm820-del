<!-- Banner -->

<h1 align="center">Hi, I'm Omar Mohammed 👋</h1>
<h3 align="center">Aspiring Data Scientist | Python Developer | Machine Learning Enthusiast</h3>

<p align="center">
  <a href="https://linkedin.com/in/omar-eprahim-9b0a3a38a">
    <img src="https://img.shields.io/badge/LinkedIn-Omar%20Mohammed-blue?style=flat-square&logo=linkedin" />
  </a>
</p>

---

## 🚀 About Me
- 🎓 Student at **Faculty of Science – Mathematics Department**  
- 🐍 Learning **Python**, **Data Science**, and **Machine Learning**  
- 📊 Interested in **Data Visualization** and practical ML basics  
- 🚀 Motivated, fast learner, and able to work under pressure  
- 🌍 Fluent in English + currently learning German  
- 💡 Passionate about self-learning and building mini projects  

---

## 🛠️ Skills & Tools

### **Languages & Libraries**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-004369?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
</p>

### **Other Skills**
- Strong **Mathematics** background  
- Problem-solving  
- Self-learning  
- Working under pressure  
- Good communication  

---

## 📂 Featured Projects

### 🔵 **1. F1 World Championships Bar Chart**
```python
import matplotlib.pyplot as plt 
import numpy as np 

drivers=["max verstappen", "lewis hamelton", "Michael Schumacher", "fernaldo alonso", "lando norris"] 
champoin=[4, 7, 7, 2, 1]

plt.bar(drivers, champoin, color="#4a1b1e")
plt.title("F1 World Championships", fontsize=20, color="black")
plt.xlabel("Drivers", fontsize=15)
plt.ylabel("Number of Championships", fontsize=15)

plt.show()
🔵 2. Multi-Line Chart for Class Size Over the Years
python
Copy code
import matplotlib.pyplot as plt 
import numpy as np 

x = np.array([2023, 2024, 2025, 2026])
y1 = np.array([15, 25, 30, 20])
y2 = np.array([17, 23, 38, 5])
y3 = np.array([13, 15, 20, 30])

plt.title("Class Size Over Years", fontsize=25, fontweight="bold")
plt.xlabel("Year", fontsize=15, fontweight="bold")
plt.ylabel("Students", fontsize=15, fontweight="bold")

plt.plot(x, y1)
plt.plot(x, y2)
plt.plot(x, y3)

plt.grid(axis="both", linewidth=1, linestyle="dashed")
plt.show()
🔵 3. Python Task Manager
python
Copy code
tasks_input = input("Enter your tasks separated by commas:\n")
tasks = tasks_input.split(", ")

finished = []
unfinished = []

for task in tasks:
    done = input(f"Did you finish {task}? (yes/no): ").lower()
    if done == "yes":
        finished.append(task)
    elif done == "no":
        unfinished.append(task)

progress = input("Do you want to see your progress? (yes/no): ").lower()

if progress == "yes":
    print("Finished tasks:", finished)
    print("Unfinished tasks:", unfinished)
else:
    print("Keep going!")
🔵 4. Simple Shopping Basket Calculator
python
Copy code
print("****** Welcome to the ISHOP Calculator ******")

item_count = int(input("How many items are in your basket? "))

basket = []
costs = []

for i in range(1, item_count + 1):
    name = input(f"Name of item {i}: ")
    price = int(input(f"Price of {name}: "))
    basket.append(name)
    costs.append(price)

if input("Show basket items? (yes/no): ").lower() == "yes":
    print(basket)

if input("Show total cost? (yes/no): ").lower() == "yes":
    print(sum(costs))
📊 GitHub Stats
Replace USERNAME with your GitHub username.

<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true" /> <br> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact" /> </p>
🌐 Connect With Me
<p align="center"> <a href="https://linkedin.com/in/omar-eprahim-9b0a3a38a"><img src="https://img.icons8.com/color/32/000000/linkedin.png"/></a> </p>
<p align="center">⭐️ Always learning. Always improving.</p> ```


