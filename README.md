# Very early alpha stage of a IHK FISI/FIAE PDF Form Berichtsheft filler.
![python-version](https://img.shields.io/badge/python-3.11-blue.svg)
[![openai-version](https://img.shields.io/badge/openai-0.27.8-orange.svg)](https://openai.com/)
[![license](https://img.shields.io/badge/License-GPL%203.0-brightgreen.svg)](LICENSE)

Now actively developing again. Expected final version by the end of August 2024.

## Technology Stack
- Flask 
- OpenAI GPT4-o
- Playwright Docker
- BeautifulSoup 

This is only for improve in programming/deploying and cause we're lazy to write this shitty forms.

## Start using Docker
Copy the .env file and edit the variables
```bash
cp .env.example .env
nano .env
```
and then run it
```bash
docker compose --env-file .env up --build -d
```

## Known Bugs?
- PDF's only looks fine in chrome. Firefox okay but looks ugly. Acrobat only shows text if you click on it. Will maybe fixed.

### Todo
Look at projects page but a little list
- [x] Login Form 
- [x] User Interface
- [ ] Add own notes to different berichtshefte
- [ ] Option to recreate the AI completion if not satisfied
- [x] Login into your moodle to see HOMEOFFICE Calculator (@1sqp)
- [x] make readme pretty x3

and more to come...
look at [Project](https://github.com/users/mxwmnn/projects/1), cause this list won't be updated

### Contribute code

Read the [Contribution Guide](https://github.com/firstcontributions/first-contributions)

then you can make a pull request to my repo :)


<h2 align="center">
    Contributors
</h2>
<p align="center">
    Thank you for your contribution!
</p>
<p align="center">
    <a href="https://github.com/mxwmnn/pdf_filler/graphs/contributors">
      <img src="https://contrib.rocks/image?repo=mxwmnn/pdf_filler" />
    </a>
</p>