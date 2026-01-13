using System;

class Task2
{
    static void Main(string[] args)
    {
        // 2D Jagged Array Initialization
        // Row 0: Even numbers
        // Row 1: Odd numbers
        int[][] numberMatrix = new int[][]
        {
            new int[] { 2, 4, 6, 8, 10 },
            new int[] { 1, 3, 5, 7, 9 }
        };

        Console.WriteLine("The number matrix has been initialized.");

        // PUZZLE DIGIT EXTRACTION
        // Digit 1: Row 1, Index 3 → value = 7
        int digit1 = numberMatrix[1][3];

        // Digit 2: Row 0, Index 0 → value = 2
        int digit2 = numberMatrix[0][0];

        // Digit 3: Row 1, Index 4 → value = 9
        int digit3 = numberMatrix[1][4];

        // Combine digits into a single string key
        string finalKey = $"{digit1}{digit2}{digit3}";

        // Final Output
        Console.WriteLine("The password is: " + finalKey);
    }
}
