1\. Test plan document for Benefiti platform

Introduction

This test plan has been created to communicate the test approach being used in project called Benefiti. It contains the scope of testing, resources, risks involved and timescale of all testing activities. The objective is to manually test features and functionalities of a software product developed for web browsers and mobile devices.

In scope

The initial phase will include main features divided by two groups \- HR and member.

HR: Define top benefits per month, Calculate total/used budget, Calculate budget spent per category, Generate usage and refund reports, Filter benefits by group/tags, Define access for benefits, Edit/delete company benefits, Add/delete an employee, Search employee field, Accept/decline refund.

Member:  Registration, Login, Upload an image, Browse benefits, Search benefits field, Filter fields, Subscribe button, Add products to favourite list, Help button, Send a message, History access, Back to dashboard button, Remaining budget/total budget.

Along with this the team will define the next steps/phase to be implemented as needed.

Out of scope

At this stage the QA team will not test website security and performance.

Risk

Team member lack required skills.

Delays in fixing errors.

The project schedule is too tight.

 

Resources

 Human Resource

Project Manager – Anastasija

QA Lead \- Aleksandra

QA Testers – course participants

Environments \+ Tools

demo.benefiti.rs

1\.       Browsers

Chrome

Safari

Edge

FireFox

2\.       Devices

iPhone 14 Pro 17.6.1

Android 15

Lap Top HP 15

3\.       Tools

Jira – Defect Tracking

Testrail – Test Cases

Snagit – Video capture/Screenshots

 

Assumptions

Required resources will be available throughout the testing period.

Support will be available if needed.

Testing activities will follow the project timeline.

 

Timescales

This platform will be tested throughout the period of two months.

| Activity | Duration |
| ----- | :---: |
| Test planning and strategy | 12 h |
| Test case design | 24 h |
| Test environment setup | 16 h |
| Test execution | 4h |
| Defect fixes | / |
| Test reporting and closure | 6h |

 

 

2.1

| EP | BV min \-1  | BV min | BV max | BV max \+1 |
| :---- | :---- | :---- | :---- | :---- |
| EP1: ? \- 90 |  |  | 90 | 91 |
| EP2: 91 \- 110 | 90 | 91 | 110 | 111 |
| EP3: 111 \- 130 | 110 | 111 | 130 | 131 |
| EP5: 131 \- ? |  | 131 |  |  |

 

2.2

| EP | BV min \-1  | BV min | BV max | BV max \+1 |
| :---- | :---- | :---- | :---- | :---- |
| EP1: ? \- 10 |  |  | 10 | 11 |
| EP2: 11 \- 15 | 10 | 11 | 15 | 16 |
| EP3: 16 \- 19 | 15 | 16 | 19 | 20 |
| EP4: 20 \- 22 | 19 | 20 | 22 | 23 |
| EP5: 22 \- ? |  | 23 |  |  |

![][image1]

| Test case | BVA |
| :---: | :---: |
| TC1 | t \= 10 |
| TC2 | t \= 11 |
| TC3 | t \= 15 |
| TC4 | t \= 16 |
| TC5 | t \= 19 |
| TC6 | t \= 20 |
| TC7 | t \= 22 |
| TC8 | t \= 23 |

2.3

| EP | TC |
| ----- | ----- |
| EP1: 8 \- 12 | TC1: newuser1 |
| EP2: ? \- 7 | TC2: user |
| EP3: 13 \- ? | TC3: onlinenewuser |
| EP4: alphanumeric | TC4: newuser1 |
| EP5: non-alphanumeric | TC5: newuser |
| EP6: uppercase | TC6: Newuser1 |
| EP7: lowercase | TC7: newuser1 |

 

 

 

[image1]: <data:image/png;base64,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CAAICu/exL8nevbZZ3/729++99579h3jm+PHj1O1/TdfC8KGqfjoo4+WLVtmS/z00083btyYSCRoOzs7+/Dhw+aN9FAe6i976ulm7AwIAJhsePcm/j3RsxL18eTJk3feeefAwIApi9bd3b1ixYqDBw+qlLy8vG9/+9v/+7//yx/pqKuuuuqLX/zikiVLurq6yOOrnDZol62owcHBLBNUmddff33evHnnn38+Fct5SAaWLl06ZcqUK6644vHHH2ctoZz+m68FYUMmHA6TEc4++2w2giblcOHChbZsQ0NDt99++4cffqjJU7MKqo30uMrhO++8s2HDhosuumj69On19fW2valgqaZ/7TtGT1AGBAAA797EvydSckgO+pe//CXp3OzZs5UcfvLJJ88995wSKk7s7+8nxXrrrbf47CRa1dXVNTU1Tz/99K233kqJBw4cMIpPwkXdeOON5qIIOtd99933tAEVfvXVV1MJ77///quvvsp56JDrr79+3759oVCItu+//35tnMkhGYHKISNQJdkIWgo5NKNUUG2kx1UO6Vi6dHjsscfYOCy0rpCpqXOrqqo0o26QQwDAuMK7N/HviZQc9vb2cjR2xhlnKDl87733SJbIC5s1jCK8b0p+9atfcaxjdvqkB9/4xjfeeOON733ve1u3blXpXJQm62z26VGJ+khQ7EiqfOaZZ3J9nnjiiUgkovZSPWfMmKGNJzlkI8TjcZVCRqA6k6FuuOGGhoaGqVOn0llUM1VY5pRDCvXWrl171lln3XPPPXTBoUlrP/nkk5ShsLCQImObHNJZ6Fzq4/DwMMWIZGoqn2VPk4bim7FZBlwIXYVADgEA4wrv3sS/J1JyqDDLIWOTQzPHjx//+te/To7Vlk5ufenSpeS+bemaQw5p+5prrpkyZQopyrFjx0wZdTZs2GCrDzN+5JCNYE+VEdhtt91WXl7e2tpKkjZz5ky+IFBhmU0O+/r6Lr744vPOO49EjlL+6Z/+iXb97ne/o+3f//73VMK//uu/2nqBrhVsYSVl7u7uplhcdQob6ojkiiuuqKysJP3WIIcAgPGHd2/i3xP5lEPKef755zvlMA22on7729+uW7fuqaeeovTLLruMQyIzVPg4l0M2gj1VyuGNN96o7l4q8Uslh3V1dbTR09NDKfRvlrzzee21165evZpL6OzstPXCww8/bDMOK59TDql8yvkP//APKp02WBd94t+AAADAePcm/j2RTzmkwOiCCy7wI4eKwcHBm2++2VnUhIgOyQj2VMezw/RySBp2ww03ZFn505/+lGUy12HHs8PMo0OWQ/O1i7qb6pMs3wYEAADGuzfx74l8ymGqZ4emLHbMRQ0PD7/00ku8TQqxaNEipxxO6GeHo5LD4uLiysrKARMkbLRLPR10ymGqZ4e0MaIcPvnkk+pAP/g3IAAAMN69iX9P5FMOCb7PyduJROLf//3fr7/+emsWCzY5vOuuu/iLE3x78OGHH7bk1rQ333xz3bp16ksXTU1NfLrxI4eaNEJLSwtvsxE+/PBDal3mcviHP/zhxz/+8Ve/+lWKNTk/qdqIN0upnMsuu6yvr48/vvbaa3V1dbTx8ccfl5eX873QcDis5PCcc85xXnD4JBADAgCANt7k0PxFC4Y8aXZ2dio51KQAXHHFFVSZpUuXsn+nEi644AKntmnyK+e2okg+v/CFL9x9992ur9IQXV1dS5YsOeuss6666ipy7iyN40oOiccff5yMMGXKFGWEj6xfw1fftVdvljq/hs9vln7+859fsGABf1+FQkwS2iz5Zun+/fudvaC+dzh16tRf/OIXKv3BBx+kypDRHnrooUsvvZTL57d229vbSSn/4z/+I823MjInKAMCAIB3b+LfEznlMBAojqG6qS8OjgXjTQ4nLTAgACAovHsT/56IRcX5W2LjHAphqdoU9Nh3jB7/NpzkwIAAgKDw7k3gifwDG/oEBgQABIV3bwJP5B/Y0CcwIAAgKLx7E3gi/8CGPoEBAQBB4d2bwBP5Bzb0CQwIAAgK794Ensg/sKFPYEAAQFB49ybwRP6BDX0CAwIAgsK7N4En8g9s6BMYEAAQFN69CTyRf2BDn8CAAICg8O5N4In8Axv6BAYEAASFd2+SBcA4wD4uAQDAE969CTyRf2BDn8CAAICg8O5N4In8Axv6BAYEAASFd28CT+Qf2NAnMCAAICi8exN4Iv/Ahj6BAQEAQeHdm8AT+Qc29AkMCAAICu/eBJ7IP7ChT2BAAEBQePcm8ET+gQ19AgMCAILCuzeBJ/IPbOgTGBAAEBTevYl/T/Tiiy9++umn9tQJwq5du/xX3r8NJzkwIAAgKLx7Ez+e6MMPP7zyyiu3bdvGH0+ePPnUU0/deeedKsMzzzyTZWLZsmWUZ+vWrWeeeebRo0c5z0cffVRfXz99+vQpU6bcfffd6tg0UDbKTAXu37//k08+0eSpm5qaKOWb3/zmz372M85G1fubv/mbu+6669133+WU3t7eiy66iLJNnTqV9nIifXznnXd42xt+bOgKNSccDn/xi188++yzlyxZMlrBJpPed999tkSq5L333js8PKxSyAKlpaWjqjyVvExi3+GPUdUBAADS4N2b+PFEJH50+JtvvqlJ35qXl0cfZ8+erTI8/PDDl19++ZNPPvm05KWXXmptbc3Ozv7ggw/uueceds3/9m//RkeRplK27373u6+99po63JW+vr6vfe1r7e3tPT09dOCePXsokf6lbUphUeSS6eyJROKnP/1pXV0dfaSSadcTTzxBNXnooYduueUWVsTLLruMM3jGjw2dkBZWV1dTmVTPffv23XrrrQcOHLBnSksqOaRrF+4sJhKJXHjhhaOqPJW8cOHCG2+80b7DH6OqAwAApMG7N/HjiRYvXvxf//VfHLtUVVVR2Ld58+avfOUrKsOGDRvIdZIPVSnPPvvs8uXL//KXv5SXl7NoUQWUBL799tt33HHH0NCQyu+EpCsWi/H2zTffTOV//PHHpMFr1qzhRFJEDj1JDklatmzZQlpLykc5i4uLVTl0XhJgTRZYUFBw/PhxtWu0+LGhE77IaGlp4Y9kvTlz5rz//vvWXOlwlcNp06ZRsWQclfLAAw9ceuml//iP/2jKNTJUMimiPdUfwRoQADCZ8e5N/HgiOvbw4cPmFFKgM844Q3286aabLr744iuuuGLq1KkNDQ0kTqa8giNHjtAhtkQz77zzzuOPP25PNSBvzoEd1YSElhOpSmpb8cgjj/z93/+9rbYMneKiiy6iDPYdGePHhk6+/vWvO8WMoMsOOlFNTQ2JPW3QpQBpPMXK5557Ln0kS951110cR7rK4bx58yg0N1eVto8dO3bJJZfQNl0N0EeKF6kc2nj99dc5A4kldRyVlmVcPUAOAQDjGe/exI8nIjUaGBgwp9jkcP78+d/5zncee+yxe+65h060c+dOU14B6VN6OUwDywNHiiPKIZ0lyyHeTDwep/CLAln7jozxY0Mn559/vlPMiDfffHP79u0ci5NusT7R1YAyAl1tzJw5k+JICrudJVDUTpp33XXXcVBOUlpRUdHd3c2Vf+GFF2gX56QUvjjIMoJU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>