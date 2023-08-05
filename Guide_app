#!/usr/bin/python3
<<<<<<< HEAD
=======

destinations = view_all_destinations()

>>>>>>> af58e860737497ff66bd5ecdff110c5e5d66c981
def display_menu():
    print("Welcome to the Tourist Guide App")
    print("1. View all destinations")
    print("2. View destination details")
    print("3. Add a new destination")
    print("4. Exit")

def view_all_destinations(destinations):
    print("All Destinations:")
    for dest in destinations:
        print(dest)

def view_destination_details(destinations):
    destination_name = input("Enter the destination name: ")
    if destination_name in destinations:
        print("Destination Details:")
        print(f"Name: {destination_name}")
        print(f"Description: {destinations[destination_name]}")
    else:
        print("Destination not found.")

def add_new_destination(destinations):
    destination_name = input("Enter the destination name: ")
    destination_description = input("Enter the destination description: ")
    destinations[destination_name] = destination_description
    print(f"{destination_name} has been added to the destinations.")

def main():
    destinations = {
        "kigali": "The City of Love and Lights.",
        "Nairobi": "The city that never sleeps.",
        "Bujumbura": "A vibrant metropolis with a rich cultural heritage.",
        "Zanzibar": "Home to the iconic Sydney Opera House and beautiful beaches."
    }

    while True:
        display_menu()
        choice = input("Enter your choice (1-4): ")

        if choice == '1':
            view_all_destinations(destinations)
        elif choice == '2':
            view_destination_details(destinations)
        elif choice == '3':
            add_new_destination(destinations)
        elif choice == '4':
            print("Thank you for using the Tourist Guide App. Have a great day!")
            break
        else:
            print("Invalid choice. Please try again.")

if __name__ == "__main__":
    main()

