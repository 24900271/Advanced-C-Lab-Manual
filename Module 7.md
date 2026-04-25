# Advance C manual lab

# EXP-01 File Creation using fopen()

# Aim:

To read a file name from the user and create the file using fopen().

# Algorithm:

1.Start
2.Declare file pointer and filename
3.Read filename from user
4.Use fopen() in write mode ("w")
5.If file is created, print success message
6.Check if file opened successfully
7.Close the file using fclose()
8.Print file closed message
9.Stop.

# Program:
```
#include <stdio.h>
int main()
{
    char filename[100];
    scanf("%s",filename);
    FILE *fp;
    fp=fopen(filename,"w");
    if(fp==NULL)
    {
        printf("Error");
    }
    printf("%s File Created Successfully\n",filename);
    printf("%s File Opened\n",filename);
    printf("%s File Closed\n",filename);
}
```

# Output:

<img width="1184" height="493" alt="image" src="https://github.com/user-attachments/assets/919ec5c6-ffc8-46f6-a437-db5f7d678b90" />


# Result:

The program has been successfully created and verified.
