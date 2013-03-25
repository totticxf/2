pair(vector<int>, int, int, int) findLongest (vector<int> a, vector<int> max, int key, int length){
pair last = findLongest (a, key, length-1);
if (last.second != length-2){
    if(a[length-2]+a[length-1]< = key)
    {vector<int> new;
     new.insert(length-2);
     new.insert(length-1);
     if(last.third<2)
         max = 2; 
     }
     else if (a[length-1]<=key){
     vector<int> new;
     new, insert(length-1)
     
     }
}

else  {
    if(last.fourth + a [length-1]<=key){
      max.insert(length-1);
      }

}
