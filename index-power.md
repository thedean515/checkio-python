

def index_power(array, n):
    try: return array[n] ** n
    except IndexError: return -1

def index_power(array, n):
    return array[n] ** n if n < len(array) else -1

