# Today:

Continued with this Angular course: 
https://youtu.be/JWhRMyyF7nc?feature=shared

And with the LinkedInLearning Videe, 

Also completed this LeetCode problem in TS: 
https://leetcode.com/problems/two-sum/description/

function twoSum(nums: number[], target: number): number[] {
    //expect to return an array of the indices that add up to the target 
    //we need to keep track of two indices 

    //first pass: 
     for(let i = 0; i < nums.length; i++){
        for(let j = i+1; j < nums.length; j++){
            if(nums[i] + nums[j] === target){
                return [i, j]
            }
        }
    }

    //using forEach 
    //example:
 /*    let result: number[];
   nums.forEach((item, index) => {
       if(nums.length < index+1){
           return;
       }else{
           if(item + nums[index+1] === target){
               console.log(item, nums[index+1])
               result = [index, index+1]
           }
       }
   })

   return result
 */
};