# Guide


Github Repo Link -   [github-link](https://www.mkdocs.org).

#### Currently supported platforms

- [codechef.com](https://codechef.com)
- [codeforces.com](https://codeforces.com)

#### Installation

``` py
    pip install getcp
```
#### Code

```py
    from getcp import cc, cf
    
    codechef_stats = cc.get_codechef_stats('username')
    codeforces_stats = cf.get_codeforces_stats('username')
    
    print("CodeChef Stats:")
    print(codechef_stats)
    
    print("\nCodeforces )Stats:")
    print(codeforces_stats
```

##### Output

###### get_codechef_stats('username')

```json
    {'rating': '805', 'solved_problems': 30,
    'rank': 'Newbie'}
```

###### get_codeforces_stats('username')

```json
    {'codechef_username': 'Wanjun Li',
    'rating': '2534', 'division': '(Div 1)',
    'stars': '7★', 'contests_participated': 76}
```

#### Dependencies

- [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
- [requests](https://pypi.org/project/requests/)


