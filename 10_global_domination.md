---
Title: Bad Snippets
Description: These might break things. Use at your own stupidity!
Date: 14 December 2018
Image: https://zdnet1.cbsistatic.com/hub/i/2018/06/18/51150a01-046d-4f30-a760-0357e6d5c2a0/e7c70a0c23a79d96645a93bd29ff3cc2/another-fun-malware-stock-image.jpg
Template: single
---

# Global Domination: Variables Gone Wild


Local variables are for the weak. Let's make everything global!

```python
def global_pandemic():
    global x, y, z
    x = 'I am x'
    y = 'I am y'
    z = 'I am z'

def global_chaos():
    global x, y, z
    print(f'{x} and {y} and {z} are partying in the global scope!')
    x, y, z = z, x, y
    print(f'Now {x} and {y} and {z} are confused about their identities.')

global_pandemic()
global_chaos()
```

This code creates global variables and then manipulates them across functions. It's a great way to create unreadable, unmaintainable code and confuse your future self. Remember, global variables are like global pandemics - best avoided!

## Key Takeaways

- This code might break things
- Use at your own risk (and stupidity)
- Python can be both powerful and dangerous

Remember, with great power comes great responsibility, and with Python, comes great potential for hilarious mistakes!

## FAQs

1. Q: Will these snippets really break things?
   A: Only one way to find out! (But seriously, be careful)

2. Q: Are there safer ways to learn Python?
   A: Probably, but where's the fun in that?

3. Q: Should I use these in production?
   A: Only if you enjoy chaos and impromptu job searches!

