# docs

How do you find all pairs of an integer array whose sum is equal to a given number?

`
pairs = []

sum = 6

arr = [1,5,7,-1,-3,9]

for i in 0..arr.length-1
  j = i + 1
  for j in j..arr.length-1
    if arr[i] + arr[j] == sum
      pairs << [arr[i], arr[j]]
    end 
  end
end
pairs
`
