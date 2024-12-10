from colorama import init, Fore
import time
import sys

init(autoreset=True)

def print_love_letter():
    love_letter = f"""
    -----------------------------------------
    {Fore.RED}💖 Dear Basma, 💖

    {Fore.CYAN}From the moment we met, my heart knew 
    that my world would never be the same. 
    Every time I see your smile, my heart 
    skips a beat, and I'm reminded of how 
    lucky I am to have you in my life. 

    {Fore.GREEN}You are my sunshine on the darkest days, 
    and my peace when everything else seems 
    chaotic. With you, I am complete, and I 
    feel a love so deep that it could never 
    be measured.

    {Fore.MAGENTA}I promise to always cherish you, laugh 
    with you, comfort you in times of sorrow, 
    and grow with you in love forever.

    {Fore.YELLOW}You're my everything, Basma. 💖
    -----------------------------------------
    """

    # Typing effect
    for char in love_letter:
        sys.stdout.write(char)
        sys.stdout.flush()
        time.sleep(0.05)  # Adjust the typing speed

print_love_letter()
