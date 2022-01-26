
# Software Engineer Interview

You're on a project to help modernize the New Mexico Department of Child Services’ (NMDCS) technology and services.

The NMDCS has an online form to help parents determine their eligibility for benefits and tell them which form they need to fill out. Currently, the online form checks if parents are eligible and how much coverage they'll receive for Child Day Care Benefits (Form B202) and Extended Care (Form D303).

The requirements and coverage percentage for the forms above are as follows:

**Child Day Care (Form B202)**
* Eligible: if the dependent is under 5
* Receives: 90% coverage if household income (HHI) is $25,000 and below
* Receives: 50% coverage if household income (HHI) is between $25,000 and $45,000
* Receives: Add an additional 10% if a single-parent household

**Extended Care (Form D303)**
* Eligible: if the dependent is 5 and older and under 13
* Receives: 90% coverage if household income (HHI) is $20,000 and below
* Receives: 50% coverage if household income (HHI) is between $20,000 and $50,000

A team of junior developers that work for the state built the current form and they're having difficulty expanding the form to determine eligibility for Special Needs Care (Form Z452).

The requirements and coverage percentage for this form are as follows:

**Special Needs Care (Form Z452)**
* Eligible: if the dependent is 13 and older and under 22
* Receives: 90% coverage if household income (HHI) is $20,000 and below
* Receives: 50% coverage if household income (HHI) is between $20,000 and  $50,000
* Receives: Add an additional 10% if a single-parent household

For the purpose of this interview, I'm one of the junior developers. Please guide me through the process of adding the new feature. You aren't expected to live code during the interview. Insteand, the “junior” developer will be writing all the code and you'll be guiding them. You're also not expected to and won't be graded on fully implementing the feature during the interview time.  

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Run your unit tests
```
npm run test:unit
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
