# 문제 1.
age_input = 25
age10 = age_input + 10
print(f"10년 뒤 당신은 {age10}세가 됩니다.")

# 문제 2.
fruits = ["사과", "바나나", "사과", "포도", "바나나", "체리"]
friuts_m = set(fruits)
print(friuts_m)
friuts_s =sorted(friuts_m)
print(friuts_s)

# 문제 3.
scores = {"국어": 90, "수학": 85, "영어": 95}
score = input()
if score != {90, 85, 95}:
    print("해당 과목의 점수가 없습니다.")

# 문제 4.
point1 = (10, 20)
point2 = (30, 40)
a = list(point1 + point2)
print(a)

# 문제 5.
search_keyword = input()

if search_keyword == "  ":
    print("검색어를 입력해주세요.")
else:
    print("'검색어'를 검색합니다.")
