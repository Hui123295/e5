import time

def concentration_timer(minutes):
    """Create a timer for a specified number of minutes."""
    seconds = minutes * 60

    for i in range(seconds, 0, -1):
        print("Time left: ", i // 60, " minutes ", i % 60, " seconds.")
        time.sleep(1)
