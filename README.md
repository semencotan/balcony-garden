# balcony-garden
def create_balcony_garden_schedule(plant_list):
    schedule = {}
    for i, plant in enumerate(plant_list, 1):
        schedule[f"Day {i}"] = plant
    return schedule

# Список растений для посадки на балконе
plant_list = ["Tomato", "Basil", "Lavender", "Chili Pepper", "Rosemary"]

# Создание расписания посадки
balcony_schedule = create_balcony_garden_schedule(plant_list)

# Вывод расписания
for day, plant in balcony_schedule.items():
    print(f"{day}: Plant {plant}")
