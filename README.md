# OldPhoneKeys
This is a coding challenge, here I upload the solution

This project simulates a old mobile phone keypad.

The 'OldPhonePadMethod' takes a string input and converts it to the corresponding text as typed on a classic phone keypad. This method simulates the behavior of typing messages on old mobile phones, where each number key corresponds to multiple letters.


# OldPhonePadMethod
The OldPhonePadMethod processes a string of key presses and converts it into a readable message according to the following rules:

Digits from 1 to 9 represent letters on a classic phone keypad.
- "*" acts as a backspace key.
- "0" acts as a space key.
- "#" represents the send key and ends the input.

# Results

Depending of the numbers you put on the test case will be give you the output that you want to see for example:

`using System:
public class OldPhonePad
{
    public static void Main(string[] args)
    {
        Console.WriteLine("Test case 1 \n");
        string input1 = "8 33 7777 8 444 66 4 0 222 666 3 33#";
        string output1 = OldPhonePadMethod(input1);
        Console.WriteLine($"Input: {input1} => Output: {output1}\n");
    }
}
`




It will print you "TESTING CODE" but you can change the message if you put another oldphonekeypad code

