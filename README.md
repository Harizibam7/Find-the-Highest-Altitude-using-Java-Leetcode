# Find-the-Highest-Altitude-using-Java-Leetcode
        class Solution {
            public int largestAltitude(int[] gain) {
                int result =0;
                int sum =0;
                for(int i =0; i<gain.length;i++){
                    sum += gain[i];
                    if(sum > result){
                        result=sum;
                    }
                }
                return result;
            }
        }
