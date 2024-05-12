# git-demo
A simple git repository to use with a class

# Metaverse Vacation Experience

class TropicalIsland:
    def __init__(self):
        self.beach = "white sandy beach"
        self.water = "crystal-clear blue water"
        self.hotel = Hotel()

class Hotel:
    def __init__(self):
        self.size = "large"
        self.amenities = ["swimming pool", "spa", "gourmet restaurant", "private cabanas"]
        self.activities = ["beach volleyball", "snorkeling", "sunset cruises"]

class Vacationer:
    def __init__(self, name):
        self.name = name
        self.wearing = "Vision Pro"

def main():
    vacationer = Vacationer("You")
    island = TropicalIsland()

    print(f"Welcome to the metaverse vacation, {vacationer.name}!")
    print(f"You're wearing your {vacationer.wearing} and standing on a {island.beach}.")
    print(f"The {island.water} stretches out before you, inviting you to take a dip.")

    # Friends
    friends = ["Alex", "Maya", "Carlos"]
    print(f"Your friends {', '.join(friends)} are nearby, laughing and enjoying the sun. Alex builds sandcastles, Maya captures photos of seashells, and Carlos plays beach volleyball.")

    # Hotel details
    print(f"The {island.hotel.size} hotel behind you offers {', '.join(island.hotel.amenities)} for your comfort.")
    print(f"Later, you'll join the {', '.join(island.hotel.activities)} at the hotel. Imagine sipping piña coladas by the pool or indulging in a relaxing massage at the spa.")

    # Sunset
    print("As the sun begins its descent, the sky transforms into a canvas of breathtaking hues:")
    print("- The deep crimson sun kisses the horizon, casting long shadows on the sand.")
    print("- The water reflects the warm colors, creating a liquid mirror that seems to stretch infinitely.")
    print("- Silhouettes of palm trees sway gently, their fronds catching the last rays of light.")
    print("- Your friends gather on the beach, toasting to another perfect day in paradise.")

    print("It's a moment frozen in time, etched into your heart—a perfect day in the metaverse!")

if __name__ == "__main__":
    main()
