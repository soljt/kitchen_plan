# Kitchen Plan

## Description

This repository contains a script that makes a kitchen plan from a calendar excel template

## Installation

### Prerequisites

Before you begin, ensure you have the following installed:

- **Python** (version 3.8 or higher)
- **pip** (Python package installer)
- **Microsoft Excel** (need this to open `.xlsx` files)

### Steps

1. **Clone the Repository**  

   Begin by cloning this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/soljt/kitchen_plan.git

2. **Navigate to the working directory**

    Just get there, you can do it!.

    ```bash
    cd kitchen_plan

3. **Get the package**

    You could use a virtual environment...but come on. There's like two libraries to install. It's all in requirements.txt. Just run this:

    ```bash
    pip install -r requirements.txt

## Usage

Great! You're ready to fire this thing up. It takes 0 or 3 command line arguments. If you provide none, it will make your plan from the default date (the first thursday in august, 2024). Just run:

```bash
python kitchen_plan.py 
```

Otherwise, you can specify the year, month, and day of the week from which you'd like your plan to start:

```bash
python kitchen_plan.py 2024 september monday
```

In either case, the script will write two files to a newly created folder, `gens`. These two files will be an excel sheet and a pdf of your new kitchen plan. Woohoo!

## Features

There are literally none! If you want to use a different list of flatmates, you'll have to hardcode that in the script yourself in the `NAMES` list! Good luck :)

## Contributing

Please don't contribute. I don't want to be shown up.

## Credits

This was done entirely by me. Cheers.

## Contact

Don't send me an email...be real. But if you absolutely have to: soljthiessen@gmail.com