# Write-a-Python-program-to-remove-spaces-from-dictionary-keys

my_dict = {
 "fruit basket": ["apple", "orange", "banana"],
 " vegetable basket ": ["carrot", "broccoli", "zucchini"],
 "animal habitat ": ["dog", "cat", "elephant", "bear"]
}
new_dict = {}
for key, value in my_dict.items():
 new_key = key.replace(" ", "")
 new_dict[new_key] = value
print(new_dict)
