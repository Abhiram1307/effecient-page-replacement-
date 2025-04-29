# Efficient Page Replacement Algorithm Simulator

An interactive simulator that visualizes and compares popular page replacement algorithms like FIFO, LRU, and Optimal in real time. Built using Python with a graphical interface and performance analysis tools, this project is ideal for students learning Operating Systems.

---

## 🔧 Features

- ✅ Simulates **FIFO**, **LRU**, and **Optimal** page replacement algorithms
- 📊 Displays **page hits**, **page faults**, and **hit/miss ratios**
- 📈 Real-time **visualization** using Matplotlib and Seaborn
- 🖥️ GUI built with **Tkinter** for easy user interaction
- 📤 Option to **export results** for further analysis
- 📚 Educational tool for understanding memory management in OS

---

## 🧠 How It Works

1. User inputs:
   - Page reference string (e.g., `7 0 1 2 0 3 0 4`)
   - Number of frames (e.g., `3`)
2. Select algorithm: FIFO, LRU, or Optimal
3. The simulator:
   - Executes the selected algorithm
   - Shows memory state step-by-step
   - Displays performance metrics
   - Visualizes results through charts

---

## 💻 Technology Stack

| Component        | Technology Used        |
|------------------|------------------------|
| GUI              | Python (Tkinter)       |
| Algorithms       | Python (FIFO, LRU, Optimal) |
| Visualization    | Matplotlib, Seaborn    |
| Data Handling    | Pandas (optional)      |
| Export/Storage   | CSV, SQLite (optional) |

---

## 📸 Screenshots

> Add screenshots of the GUI, graphs, and execution results here.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed. Then install required libraries:

```bash
pip install matplotlib seaborn pandas

TO Run the Simulator: 
python main.py

Project Structure

├── main.py                 # Entry point
├── algorithms.py           # Contains FIFO, LRU, Optimal
├── gui.py                  # GUI interface with Tkinter
├── visualizer.py           # Chart and graph logic
├── utils.py                # Helper functions
├── README.md               # Project documentation