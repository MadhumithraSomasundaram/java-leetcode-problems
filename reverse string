public class Solution {
    public void reverseString(char[] s) {
        int left = 0;
        int right = s.length - 1;

        // Swap characters until the two pointers meet
        while (left < right) {
            // In-place swap using a temporary variable
            char temp = s[left];
            s[left] = s[right];
            s[right] = temp;

            // Move the pointers
            left++;
            right--;
        }
    }
}
