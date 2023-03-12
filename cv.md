# Anu Felia

---

#### Junior Frontend Developer

---

#### Contact information:

---

1.Email: lujvn@mail.ru\
2.Github: https://github.com/ang899

#### Other informalion:

---

I’m a junior frontend developer. I do my best to upgrade my skills.\
I have bachelor and master degree in chemistry and IT basic certificate.

#### Skills and Proficiency:

---

- HTML
- CSS
- basic JS
- basic C#
- Jira

#### Code example:

---

A Narcissistic Number (or Armstrong Number) is a positive number which is the sum of its own digits, each raised to the power of the number of digits in a given base. In this Kata, we will restrict ourselves to decimal (base 10). Your code must return true or false (not 'true' and 'false') depending upon whether the given number is a Narcissistic number in base 10.

```
using System;
public class Kata
{

  public static bool Narcissistic(int value)
        {

            int[] numb = new int[10];
            int curr = value;
            int i = 0;
            while (curr >9)
            {
                numb[i] = curr%10;
                curr = (curr - numb[i]) / 10;
                i++;
            }

            numb[i] = curr;
            int a = i+1;
            int valuecurr = 0;
            for (i = 0; i < a; i++)
            {
                valuecurr = valuecurr + (int)Math.Pow(numb[i], a);
            }

            if (valuecurr == value)
            { return true; }
            else
            { return false; }

        }
}

```

#### Languages:

---

1.Russian - native\
2.English - B2
