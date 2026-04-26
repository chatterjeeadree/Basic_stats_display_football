#Basic match stats

# team_names

t1 = input("Enter team 1 : ")
t2 = input("Enter team 2 : ")

#team_goals

t1_goals = int(input("Enter goals scored by team 1 : "))
t2_goals = int(input("Enter goals scored by team 2 : "))

#taking scorers

scorers_1 = []
for goals in range(t1_goals):
    scorers_1.append(input(f"Enter scorer name for {t1} : "))

scorers_2 = []
for goals in range(t2_goals):
    scorers_2.append(input(f"Enter scorer name for {t2} : "))

#goal minutes

minutes_1 = []
for i in range(t1_goals):
  minutes_1.append(int(input(f"Enter minute of goal scored by {scorers_1[i]} for {t1} : ")))


minutes_2 = []
for i in range(t2_goals):
  minutes_2.append(int(input(f"Enter minute of goal scored by {scorers_2[i]} for {t2} : ")))

#results

print("----------------------------Final score-----------------------------\n")

print("             ",t1,   t1_goals,"         :          ",t2_goals,     t2,"        \n")


max_scorers = max(len(scorers_1), len(scorers_2))


if scorers_1 or scorers_2:
    for i in range(max_scorers):

        scorer1 = scorers_1[i] if i < len(scorers_1) else ""
        scorer2 = scorers_2[i] if i < len(scorers_2) else ""


        print(f"{scorer1:<25} {scorer2:>35}")

print("\n--------------------------------------------------------------------")

