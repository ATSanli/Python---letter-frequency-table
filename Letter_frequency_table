def letter_frequency_table(input_string):
    # Create an empty dictionary to store the letter frequencies
    freq_table = {}

    # Convert the input string to lowercase
    input_string = input_string.lower()

    # Loop through each character in the input string
    for char in input_string:
        # Ignore non-alphabetic characters
        if char.isalpha():
            # If the character is already in the frequency table, increment its count
            if char in freq_table:
                freq_table[char] += 1
            # Otherwise, add it to the frequency table with a count of 1
            else:
                freq_table[char] = 1

    # Create an empty dictionary to store the frequency of each letter in the alphabet
    alphabet_freq_table = {}

    # Loop through each letter in the alphabet
    for letter in "abcdefghijklmnopqrstuvwxyz":
        # If the letter is in the frequency table, add its frequency to the alphabet frequency table
        if letter in freq_table:
            alphabet_freq_table[letter] = freq_table[letter]
        # Otherwise, add it to the alphabet frequency table with a frequency of 0
        else:
            alphabet_freq_table[letter] = 0

    # Return the alphabet frequency table
    return alphabet_freq_table

# Example usage
input_str = "This homework was awesome"
freq_table = letter_frequency_table(input_str)
print(freq_table)
 
