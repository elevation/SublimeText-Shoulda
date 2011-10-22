# Sublime Text 2 - Shoulda Matcher Snippets
[*Thoughtbot Shoulda Matchers*](https://github.com/thoughtbot/shoulda-matchers)

## Installation
```bash
cd ~/Library/Application Support/Sublime Text 2/Packages
git clone git@github.com:ChuckJHardy/SublimeText-Shoulda.git Shoulda
```

## ActiveRecord
(tab) - Indicated Type and Hit Tab

itsh(tab) `it { should }`
itshbt(tab) `it { should belong_to(:MODEL) }`
itshhm(tab) `it { should have_many(:MODEL) }`
itshhmt(tab) `it { should have_many(:MODEL).through(:MODEL) }`