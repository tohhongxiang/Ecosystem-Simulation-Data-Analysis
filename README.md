# Ecosystem Simulation Data Analysis

Used in conjunction with [Ecosystem Simulation](https://github.com/tohhongxiang123/Ecosystem-Simulation) to perform data analysis

# Setup

```
git clone https://github.com/tohhongxiang123/Ecosystem-Simulation-Data-Analysis.git
cd Ecosystem-Simulation-Data-Analysis

python -m venv venv
venv/Scripts/activate
pip install numpy pandas matplotlib seaborn
```

# Deer Only

These settings got a balanced ecosystem:

Deer: 

| Stats                        | Value |
| ---------------------------- | ----- |
| Speed                        | 1.2   |
| Size                         | 1.2   |
| Hunger Decrease Factor       | 0.33  |
| Thirst Decrease Factor       | 0.29  |
| Stamina Decrease Factor      | 4     |
| Gestation Duratino           | 3     |
| Duration between Pregnancies | 3     |
| FOV Range                    | 30    |
| Grow into Adult Duration     | 17    |
| Expected Age                 | 750   |

Terrain Grass:

| Setting                          | Value |
| -------------------------------- | ----- |
| Minimum Spawn Height             | 0.1   |
| Maximum Spawn Height             | 1     |
| Max Angle from Vertical          | 30    |
| Number of prefabs per 100 meters | 1     |
| Should respawn                   | True  |
| Respawn All missing at once      | True  |
| Minimum Time Between Respawn     | 1     |