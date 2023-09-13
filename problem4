class Solution {
public:
    double findMedianSortedArrays(vector<int>& nums1, vector<int>& nums2) {
        vector<int>m(nums1);
for(auto i :nums2){
    m.emplace_back(i);
}
sort(m.begin(),m.end());
int n = m.size();
if(n%2!=0){
    double start =0;
    double end = m.size()-1;
    double mid = start +(end -start)/2;
    return m[mid];
    
}else{
    double start = 0;
    double end = m.size()-1;
    int mid = start +(end -start)/2;
    double f = (m[mid]);
    double s = (m[mid+1]);
    double ans = (f+s)/2;
    return ans;
}
return -1;
    }
};
