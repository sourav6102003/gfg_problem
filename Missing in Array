class Solution {
  public:
    int missingNum(vector<int>& arr) {
        int n=arr.size()+1;
        int originalsum=0;
        for(int i=1;i<=n;i++)originalsum+=i;
        int actualsum=0;
        for(int i=0;i<arr.size();i++)actualsum+=arr[i];
        return originalsum-actualsum;
        
    }
};
