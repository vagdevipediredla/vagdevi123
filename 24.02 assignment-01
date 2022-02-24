def count_primes_in_list(numbers):
    primes = []

    for num in numbers:
        if num == 2:
            primes.append(num)
        else:
            is_prime = True
            for i in range(2, num):
                if num % i == 0:
                    is_prime = False
                    break

            if is_prime:
                print (num)
                primes.append(num)

    return len(primes)


z = [4, 5, 6, 7, 8, 9, 10,11]
print ("the count is",count_primes_in_list(z))
