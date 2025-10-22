import time
def stopwatch(duration=3):
    print("🕐 Stopwatch started...")
    start = time.time()
    time.sleep(duration)
    end = time.time()
    print(f"Elapsed time: {round(end - start, 2)} seconds")

if __name__ == "__main__":
    stopwatch()
