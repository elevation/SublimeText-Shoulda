# Sublime Text 2 - Shoulda Matcher Snippets
[*Thoughtbot Shoulda Matchers*](https://github.com/thoughtbot/shoulda-matchers)

## Installation
```bash
cd ~/Library/Application Support/Sublime Text 2/Packages
git clone git@github.com:ChuckJHardy/SublimeText-Shoulda.git Shoulda
```

## Tab Completion
#### ActiveRecord

itsh `it { should }`

itshbt `it { should belong_to(:MODEL) }`

itshhm `it { should have_many(:MODEL) }`

itshhmt `it { should have_many(:MODEL).through(:MODEL) }`