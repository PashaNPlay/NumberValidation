
/*
NumberValidation
*/

public class Solution {
    public static boolean checkTelNumber(String telNumber) {
        if (telNumber == null) {
            return false;
        }

        return telNumber.length() == 10 && telNumber.matches("\\d{10}") ||
                telNumber.length() == 13 && telNumber.matches("\\+\\d{12}") ||
                telNumber.length() == 12 && telNumber.matches("\\d*\\(\\d{3}\\)\\d+") ||
                telNumber.length() == 15 && telNumber.matches("\\+\\d*\\(\\d{3}\\)\\d+");
    }

    public static void main(String[] args) {

    }
}
