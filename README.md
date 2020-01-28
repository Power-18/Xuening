# Xuening
int subarraySum(int* nums, int numsSize, int k){
    int i,j;
    int sum=0;
    int n=0;
    for(i=0;i<numsSize;i++){
        sum=0;
        for(j=i;j<numsSize;j++){
            sum=sum+nums[j];
            if(sum==k) 
              n++;
        }
    }    
    return n;
}
