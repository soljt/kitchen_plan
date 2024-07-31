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

    ```bash
    cd kitchen_plan

3. **Get the package**

    You could use a virtual environment...but come on. There's like two libraries to install. It's all in requirements.txt. Just run this:

    ```bash
    pip install -r requirements.txt

## Usage

Great! You're ready to fire this thing up. It takes 0, 1, 3, or 4 command line arguments. If you provide none, it will make your plan from the default date (the first thursday in august, 2024) and use the hardcoded list of flatmate names. Just run:

```bash
python kitchen_plan.py 
```

If you want to specify the list of flatmates via the command line, you can run:

```bash
python kitchen_plan.py edit
```

If you want to use the hardcoded list of flatmates, but you stil want to specify the year, month, and day of the week from which you'd like your plan to start, you can run:

```bash
python kitchen_plan.py 2024 september monday
```

And finally, if you want to specify the year, month, day of the week from which you'd like your plan to start, AND the list of flatmates via the command line, you can run:

```bash
python kitchen_plan.py 2024 september monday edit
```

In any case, the script will write two files to a newly created (or pre-existing) folder, `gens`. These two files will be an excel sheet and a pdf of your new kitchen plan. Woohoo!

## Features

There are literally none! Enjoy :)

## Contributing

Please don't contribute. I don't want to be shown up.

## Credits

This was done entirely by me. Cheers.

## Contact

Don't send me an email...be real. But if you absolutely have to: soljthiessen@gmail.com