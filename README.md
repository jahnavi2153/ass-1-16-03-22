# ass-1-16-03-22
#Write a program to remove duplicates from the digit.
def Remove(duplicate):
    n=[]
    for num in duplicate:
        if num not in n:
            n.append(num)
    return n
duplicate=[1,2,1,4,4,5,6]
print(Remove(duplicate))

output:
[1,2,4,5,6]
