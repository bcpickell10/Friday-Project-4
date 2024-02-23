# Friday-Project-4
AI generated code for all previous Friday projects in DS-3850

import random

def generate_powerball_numbers():
    # Generate first four numbers from 1 to 69
    first_four_numbers = [random.randint(1, 69) for _ in range(4)]
    
    # Generate the fifth number from 1 to 26 (Powerball number)
    powerball_number = random.randint(1, 26)
    
    return sorted(first_four_numbers), powerball_number

def main():
    print("Welcome to the Powerball Number Generator!")
    input("Press Enter to generate your lucky numbers...")
    
    # Generate Powerball numbers
    first_four, powerball = generate_powerball_numbers()
    
    print("Your lucky numbers are:")
    print("Main Numbers:", first_four)
    print("Powerball Number:", powerball)

if __name__ == "__main__":
    main()


    