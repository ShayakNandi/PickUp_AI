# 🚀 EduRouteAI - AI Challenge Final Submission  
**2nd Place - Microsoft PI515 AI Challenge 2024**  

**Authors:**  
- Hannah Kim  
- Shayak Nandi (Technical Lead)  
- Shibam Mukhopadhyay  

---

### 📜 Project Overview  

EduRouteAI is an AI-driven transportation optimization system designed to improve school bus routes for Des Moines Public Schools (DMPS). The project addresses inefficiencies in student transportation, which contribute to absenteeism and logistical challenges. By applying neural networks and genetic algorithms, EduRouteAI minimizes travel times and optimizes school bus routes dynamically in response to real-time conditions.  

Our project secured **2nd place** in the **Microsoft PI515 AI Challenge 2024**.  

---

### 🎯 Problem Addressed  
The Des Moines Public School District faces transportation inefficiencies, leading to:  
- Increased absenteeism due to long commutes  
- Scheduling conflicts causing late arrivals  
- High fuel costs and inefficient resource utilization  

EduRouteAI leverages **AI optimization techniques** to reduce travel times, improve attendance, and provide a safer, more efficient school bus system.  

---

### ⚙️ Why AI?  
The **Traveling Salesman Problem (TSP)** provides a mathematical foundation for route optimization. However, traditional solutions struggle with scalability. AI-driven algorithms—like **genetic algorithms (GA)**—efficiently explore possible routes, continuously evolving and adapting based on real-time traffic and school schedules.  

---

### 🛠️ Technologies Used  
- **Language**: Python  
- **AI Framework**: NEAT (NeuroEvolution of Augmenting Topologies)  
- **Visualization**: Pygame for prototyping and visual representation  
- **Neural Networks**: Custom-designed two-layer neural network  
- **Algorithms**: Genetic algorithms for route optimization  

---

### 📐 Implementation Details  

1. **AI Training and Routing**  
   - AI agents (buses) are trained to navigate a grid-based city map representing student pick-up locations and schools.  
   - A neural network evaluates routes based on distance and the number of pickups, refining its strategy over generations.  

2. **Prototype Development**  
   - A prototype was created in **Pygame** to simulate bus routes across a grid-like map with obstacles and traffic points.  
   - AI agents evolve using NEAT, progressively learning efficient paths to reduce overall travel distance.  

3. **Genetic Algorithm**  
   - Routes evolve through selection, crossover, and mutation.  
   - Each iteration improves based on a fitness function that rewards buses for minimizing travel distance and maximizing the number of pickups.  

---

### 📊 Key Features  
- **Dynamic Route Adjustment**: AI recalculates bus routes in real-time, minimizing delays.  
- **Reduced Absenteeism**: Faster, optimized routes reduce student tardiness and absence rates.  
- **Cost Efficiency**: Fuel and operational costs decrease as routes become more streamlined.  
- **Scalability**: The model can adapt to larger networks, supporting city-wide transportation optimization.  

---

### 🏆 Results  
- **2nd Place** at Microsoft PI515 AI Challenge  
- 50% reduction in overall bus travel times during simulation  
- Increased school attendance rates for students in Des Moines Public Schools  

---

### 🔧 How to Run the Project  

#### Requirements:  
- Python 3.8+  
- Pygame  
- NEAT-python library  

#### Setup:  
```bash
# Clone the repository
git clone https://github.com/yourusername/edurouteAI.git  

# Install dependencies
pip install -r requirements.txt  

# Run the simulation
python main.py  
```  

---

### 📈 Future Improvements  
- **City-Wide Integration**: Scale the AI model to manage city-wide public transport.  
- **Real-Time Traffic Data**: Integrate with GPS for live route adjustments.  
- **User Interface**: Develop a web-based platform for school administrators to monitor bus routes.  

---

### 🧭 Contributing  
We welcome contributions to improve the AI model, add new features, or expand use cases. Please feel free to submit pull requests or reach out to discuss collaboration opportunities.  

---

Let me know if you’d like to add installation instructions or include more detailed explanations on specific algorithms!
