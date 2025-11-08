def percentage_of(part, whol):
    if whole == 0:
        return 0
    return (part / whole) * 100

if __name__ == "__main__":
    part = 25
    whole = 200
    print(f"{part} is {percentage_of(part, whole)}% of {whole}")
