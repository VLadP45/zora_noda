# zora_nodadef zora_noda():
    for i in range(1, 101):
        if i % 3 == 0 and i % 5 == 0:
            print("ZoraNoda")
        elif i % 3 == 0:
            print("Zora")
        elif i % 5 == 0:
            print("Noda")
        else:
            print(i)

# Run the function
zora_noda()
