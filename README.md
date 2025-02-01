class Solution {
    public boolean rotateString(String s, String goal) {

    
        
        if (s.length() != goal.length()) {
            return false;
        }
        String doubledS = s + s;
        return doubledS.contains(goal);
    }
}

OutPut

![image](https://github.com/user-attachments/assets/851ab30e-1f1d-4830-abc7-0710e1c347bb)
