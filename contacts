contacts = []

def add_contact():
    name = input("Введіть ПІБ контакту: ")
    contacts.append(name)
    print(f"Контакт '{name}' додано!")

def show_contacts():
    if not contacts:
        print("Список контактів порожній.")
    else:
        print("\nВаші контакти:")
        for contact in contacts:
            print(f"- {contact}")

while True:
    print("\n1. Додати контакт")
    print("2. Переглянути список")
    print("3. Вийти")
    
    choice = input("Оберіть дію (1-3): ")
    
    if choice == '1':
        add_contact()
    elif choice == '2':
        show_contacts()
    elif choice == '3':
        print("Вихід з програми.")
        break
    else:
        print("Помилка: оберіть пункт 1, 2 або 3.")
