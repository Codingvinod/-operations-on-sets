# -operations-on-sets
#union operation
set1={'rajesh' , 'vinu' , 'vali'}
set2={'gowthami' , 'sana' , 'vali'}
print(set1.union(set2))
print(set1)
#another way to slove
set1={'jenny', 'priya','chinnu'}
set2={'kanna','bangaram','chinnu'}
print(set1|set2)
#intersection operation
set1={'jenny', 'priya','chinnu'}
set2={'kanna','bangaram','chinnu'}
print(set1.intersection(set2))
#another way to slove
set1={'jenny', 'priya','chinnu'}
set2={'kanna','bangaram','chinnu'}
print(set1 & set2)
#difference between 2 sets
set1={'jenny', 'priya','chinnu'}
set2={'kanna','bangaram','chinnu'}
print(set1.difference(set2))
#another way to slove 
set1={'jenny', 'priya','chinnu'}
set2={'kanna','bangaram','chinnu'}
print(set1 - set2)
#disjoint sets in python their is common elements in the sets 
set1={'rajesh' , 'vinu' , 'vali'}
set2={'gowthami' , 'sana' , 'vali'}
print(set1.isdisjoint(set2))
#disjoint sets in python their is no common elements between the sets
set1={'rajesh' , 'vinu' , }
set2={'gowthami' , 'sana' , 'vali'}
print(set1.isdisjoint(set2))
#their is no names between the set
print(set1.isdisjoint(['jhony','priya']))
#in this case sana is in the set2 
print(set2.isdisjoint(['sana']))
set1={'rajesh' , 'vinu' , }
set2={'gowthami' , 'sana' , 'vali'}
print(set1.issubset(set2))
set1={'rajesh' , 'vinu' ,'sana' }
set2={'gowthami' , 'vinu' , 'vali'}
print(set1.issubset(set2))

