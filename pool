import time

def filtration():
    # code for filtration mode
    print("Switching to filtration mode...")
    time.sleep(2)
    print("Filtration mode activated!")
    # code to filter and heat water and work with vacuum cleaner

def backwash():
    # code for backwash mode
    print("Switching to backwash mode...")
    time.sleep(2)
    print("Backwash mode activated!")
    # code to clean filter by reversing water flow and discharging into sewer

def rinse():
    # code for rinse mode
    print("Switching to rinse mode...")
    time.sleep(2)
    print("Rinse mode activated!")
    # code to compact sand and drain water into sewer

def waste():
    # code for waste mode
    print("Switching to waste mode...")
    time.sleep(2)
    print("Waste mode activated!")
    # code to bypass filter and discharge water into sewer

def recirculation():
    # code for recirculation mode
    print("Switching to recirculation mode...")
    time.sleep(2)
    print("Recirculation mode activated!")
    # code to bypass filter and return water to pool

def closed():
    # code for closed mode
    print("Switching to closed mode...")
    time.sleep(2)
    print("Closed mode activated!")
    # code to close everything

def clean_filter():
    # code to clean filter
    print("Cleaning filter...")
    time.sleep(2)
    print("Backwash mode activated!")
    # code to monitor degree of filter cleaning, rinse, and switch back to filtration mode

def clean_skimmer_and_pump():
    # code to clean mesh buckets inside skimmer and filter pump
    print("Cleaning mesh buckets inside skimmer and filter pump...")
    time.sleep(2)
    print("Mesh buckets cleaned!")

# main code
print("Welcome to the swimming pool water purification system!")
while True:
    print("\nPlease select a mode:\n1. Filtration\n2. Backwash\n3. Rinse\n4. Waste\n5. Recirculation\n6. Closed")
    mode = input("Enter mode number: ")

    if mode == "1":
        filtration()
    elif mode == "2":
        backwash()
        clean_filter()
    elif mode == "3":
        rinse()
    elif mode == "4":
        waste()
    elif mode == "5":
        recirculation()
    elif mode == "6":
        closed()
    else:
        print("Invalid mode number. Please try again.")

    clean_skimmer_and_pump() # clean mesh buckets inside skimmer and filter pump after each mode

