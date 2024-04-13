## Guide


Github Repo Link -   [github-link](https://github.com/UD11/getcp-pkg?tab=readme-ov-file).

### Currently supported platforms

- [codechef.com](https://codechef.com)
- [codeforces.com](https://codeforces.com)
- [Github.com](https://github.com/)

### Installation

``` py
    pip install getcp
```
### Code

```py
    from getcp import cc, cf, github
    
    codechef_stats = cc.get_codechef_stats('username')
    codeforces_stats = cf.get_codeforces_stats('username')
    github_info = github.get_github_stats('username')
    
    print("CodeChef Stats:")
    print(codechef_stats)
    
    print("\nCodeforces Stats:")
    print(codeforces_stats)
    
    print("\nGithub Info:")
    print(github_info)

```

#### Output

##### get_codechef_stats('username')

```json
    {'rating': '805', 'solved_problems': 30,
    'rank': 'Newbie'}
```

##### get_codeforces_stats('username')

```json
    {'codechef_username': 'Wanjun Li',
    'rating': '2534', 'division': '(Div 1)',
    'stars': '7★', 'contests_participated': 76}
```

##### get_github_stats('username')
    
```json
    {'name': 'Abhoy Sarkar', 'location': 'Kolkata, India',
    'repo_info': [
    {'repo_name': 'bytedrop', 'link': '/abhoy21/bytedrop', 'lang': 'TypeScript', 'update': 'Apr 11, 2024'},
    {'repo_name': 'leetcode', 'link': '/abhoy21/leetcode', 'lang': 'C++', 'update': 'Apr 11, 2024'},
    {'repo_name': 'my_portfolio', 'link': '/abhoy21/my_portfolio', 'lang': 'JavaScript', 'update': 'Apr 4, 2024'},
    {'repo_name': 'abhoy21', 'link': '/abhoy21/abhoy21', 'lang': 'Not Specified', 'update': 'Mar 31, 2024'},
    {'repo_name': 'sensei_frontend', 'link': '/abhoy21/sensei_frontend', 'lang': 'TypeScript', 'update': 'Mar 29, 2024'},
    {'repo_name': 'sensei_backend', 'link': '/abhoy21/sensei_backend', 'lang': 'Python', 'update': 'Mar 29, 2024'},
    {'repo_name': 'apple_ui', 'link': '/abhoy21/apple_ui', 'lang': 'JavaScript', 'update': 'Mar 17, 2024'},
    {'repo_name': 'sloka_frontend', 'link': '/abhoy21/sloka_frontend', 'lang': 'TypeScript', 'update': 'Feb 24, 2024'},
    {'repo_name': 'sloka_backend', 'link': '/abhoy21/sloka_backend', 'lang': 'Python', 'update': 'Feb 20, 2024'}]}
```

### Dependencies

- [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
- [requests](https://pypi.org/project/requests/)


