# Makovetsky Dmitry


## Contacts

Telephone: +375447197137
Discord: Skade#8787


## Briefly about myself


I believe my abilities will help me to become a Frontend Developer


## Skills and proficiency:
* HTML and CSS
* Javascript Basics
* Angular Basics
* C# Basics
* Git and GitHub
* Adobe Photoshop


## Code Example
Highest and Lowest kata frome Codewars: In this little assignment you are given a string of space separated numbers, and have to return the highest and lowest number.
```
using System;

public static class Kata
{
  public static string HighAndLow(string numbers)
  {
    string[] numsS=numbers.Split(" ");
    int[] nums=new int[numsS.Length];
    for(int i=0; i<numsS.Length; i++)
        nums[i]=int.Parse(numsS[i]);
    int max=nums[0], min=nums[0];
    for(int i=0;i<nums.Length;i++)
    {
      if(nums[i]>max)
        max=nums[i];
      if(nums[i]<min)
        min=nums[i];
    }
    return max.ToString()+" "+min.ToString();
  }
}
```


## Courses
* Frontend deeveloper courses by MyItSchool
* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)


## Languages
English - B2
Russian - Native
