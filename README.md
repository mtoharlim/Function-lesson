# Function-lesson
> BMI = weight_kg, height_m

```
# BMI calculator

name1 = "YK"
height_m1 = 2
weight_kg1 = 90

name2 = "YK"
height_m2 = 1.8
weight_kg2 = 70

name3 = "YK"
height_m3 = 2.5
weight_kg3 = 160

# function calculate

def bmi_calculator(name, height_m, weight_kg):
    bmi = weight_kg / (height_m **2)
    print("bmi: ")
    print(bmi)
    if bmi < 25:
        return name + " is not overweight"
    else:
        return name + " is overweight"
# Calculate
result1 = bmi_calculator(name1, height_m1, weight_kg1)
result2 = bmi_calculator(name2, height_m2, weight_kg2)
result3 = bmi_calculator(name3, height_m3, weight_kg3)

# Show output
print(result1)
print(result2)
print(result3)


```
## Output BMI
- YK is not overweight
- YK is not overweight
- YK is overweight

> Kilomater convert to miles

```
def convert(miles):
    km = 1.6*miles
    print("KM : ",(km))
    if km < 10:
        return " is short"
    else:
        return  " is long"
 
 # Show output
 convert(2)
 
 ```
 
 ## Output KM
- KM :  3.2
- ' is short'
 
