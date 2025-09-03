class Solution {
    int missingNum(int arr[]) {
        // code here
        Arrays.sort(arr);
        int n=arr.length;
        int num=1;
        for(int i=0; i<n; i++){
            if(arr[i] == num){
                num++;
            }
            else{
                return num;
            }
        }
        return num;
    }
}
