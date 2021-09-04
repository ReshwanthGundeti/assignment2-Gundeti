# assignment2-Gundeti

# RESHWANTH GUNDETI

###### THIRUPATHI

It is quite amazing and had a wonderful time visiting the **golden temple**.
The entire atmosphere filled with a kind of **positive energy**.

---

### Route Map

1. Go to the Kansas city airport   
2. Board a flight to India
    1. Book a bus to thirupathi
    2. Book a free darshan ticket
    3. Visit golden temple      
* Laddu
* Lemon rice
* Pongal

[AboutMelink](AboutMe.md)   

---

###  Recommended Food

The below table shows the recommended Food items and Location, the Amount to be paid for their purchase.

|   Food Items     |      Location      |    Amt(INR)    |
|    ---           |      ---           |     ---        |     
|    Biryani       |      Hyderabad     |  150           |
|                  |                    |                |
|    Shawarma      |     Kolkata        |     100        |
|                  |                    |                |
|    Kajukatli     |     Delhi          |      500       |
|                  |                    |                |
|    Ravva Dosa    |       Telangana    |     80         |

---

#### Inspiring Quotes
> Die with memories,not with dreams - *Alexnader*   
> What you become in the process is more important than the dream - *Robert T.Kiyosaki*

---

### Algebra 

> The word algebra is also used in certain specialized ways. A special kind of mathematical object in abstract algebra is called an "algebra" 
(<https://en.wikipedia.org/wiki/Algebra>)

```
pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}

```
Link : <https://cp-algorithms.com/algebra/fibonacci-numbers.html>




