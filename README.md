# Barking-Dog
This program tells you to wake depending on the time your dog is barking. 



public class BarkingDog {

    public static boolean shouldWakeUp(boolean barking, int hourOfDay) {

        if(barking && hourOfDay >= 0 && hourOfDay <= 23 && (hourOfDay < 8 || hourOfDay > 22))
            return true;
        else return false;
    }
    public static void main(String[] args) {
        System.out.println(shouldWakeUp(true, -1));
    }
}

<img width="1278" alt="Screenshot 2021-12-24 at 9 58 15 AM" src="https://user-images.githubusercontent.com/96517341/147343094-d841e901-7477-4623-a6b3-8a66eed799be.png">
