# Fair and Balanced

## Questions

1. Yes

2. Yes

3.

```c
bool balanced (int a[], int n)
{
    // Declare variables for the sum of left and right side and initialize to 0
    int left = 0;
    int right = 0;

    // Declare a variable for the halfway point
    int half = n / 2;

    // Add all the left side array elements together
    for (int i = 0; i < half; i++)
    {
        left += a[i];
    }

    // Add all the left side array elements together
    for (int j = n - 1; j >= half; j--)
    {
        right += a[j];
    }

    // Check if both sides are equal
    bool result = left == right ? true : false;
    return result;
}
```

## Debrief

1. My Brain

2. 1 hour
