

# Snake-AI

The Snake AI is a game to eat apple  and avoid collision with itself. The snake can grow by eating apples, but if it hits wall or himself it will die

## Prerequisites

Before you can start using the SNAKE-AI, make sure you have the following prerequisites installed on your system:
Download gplk solver for windows or linux from official site

- Python 3.6 or higher
- Required Python packages (you can install them using pip):
    - pygame
    -numpy
    -pandas
    -stable_baselines3
    -gym
    -Shimmy
    -gymnasium

## Installation

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/prashantpandya000/snake-AI.git
    cd snake-AI
    ```

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```
4. Run the code:

    ```bash
    python snake_ppo/model_play.py
    ```