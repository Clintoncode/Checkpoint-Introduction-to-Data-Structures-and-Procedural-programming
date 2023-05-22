# Checkpoint-Introduction-to-Data-Structures-and-Procedural-programming

problem 1
To solve this problem using arrays, you can follow these steps:

Combine the elements from both sets into a single array.
Create an empty array to store the distinct elements.
Iterate through each element in the combined array.
For each element, check if it is already present in the distinct array.
If it is not present, add it to the distinct array.
If it is already present, skip to the next element.
After iterating through all the elements, calculate the sum of the distinct array elements.
Return the sum as the output

problem 2

Procedure dot_product(v1, v2: vector of IR; VAR ps: IR)
    ps := 0
    For i from 0 to length(v1)-1 do
        ps := ps + (v1[i] * v2[i])
    End For
End Procedure

Algorithm DetermineOrthogonality
    Input: n (number of pairs of vectors)
    For each pair of vectors (v1, v2) from 1 to n do
        Read v1, v2 (vectors of IR)
        ps := 0 (initialize dot product variable)
        Call dot_product(v1, v2, ps) (calculate the dot product)
        If ps = 0 then
            Write "Vectors are orthogonal"
        Else
            Write "Vectors are not orthogonal"
        End If
    End For
End Algorithm
