# **Maksim Ivashniou**

## **Contact information:**

**Location:** Belarus, Mogilev

**Phone:** +375295449801

**E-mail:** maksim.ivashniou@gmail.com

[Telegram](https://t.me/Maksim_Ivashniou)

[GitHub](https://github.com/MaksimIvashniou)

[LinkedIn](https://www.linkedin.com/in/maksim-ivashniou-2087191a4/)

## **About Myself:**

Hello. I'm 25 years old. I'm learning back-end development. I joined the EPAM lab in the QA department in 2019 and got an amazing teamwork experience. I went to RS School on the recommendation of an EPAM employee to improve my front-end development skills.

## **Skills**

### **Programming langeages:**

- С# (Intermediate)
- HTML5 (Intermediate)
- CSS3 (Intermediate)
- JavaScript (Intermediate)
- TypeScript (Pre-Intermediate)

### **Frameworks, Tools:**

- .NET, .NET Core (Intermediate)
- ASP.NET (Intermediate)
- Entity Framework (Intermediate)
- Angular 2+ (Pre-Intermediate)
- SQL (Pre-Intermediate)
- SSMS (Pre-Intermediate)
- Postman API (Basics)
- Git (Intermediate)
- JIRA (Pre-Intermediate)

### **Soft:**

- Good working experience based on kanban methodology
- Newcomers onboarding and adaptation

## **Code examples**

```
static uniqueLoginValidator(authService: AuthenticationService, findLikeDublicate: boolean): AsyncValidatorFn {
    return (control: AbstractControl): Observable<ValidationErrors> => {
      let data: UserAuth = {
        login: control.value
      }

      return authService.checkLogin(data)
        .pipe(
          map((result: boolean) => {
            return (result === findLikeDublicate) ? { isDboValue: true } : {}
          }));
    }
  }
```

## **Education**

- Belarussian-Russian University
  - Engineering-Economic department

## **Experience**

- QA Tester (trainee): July 2019 - April 2020

## **Cources**

- RS School Cource "[JS/FE Pre-School 2022Q2](https://app.rs.school/certificate/b6u5ds5a)" - 01.06-04.09.2022
- RS School Cource "JS/FE Pre-School 2024Q2" - **In progress**

## **Languages**

- Belarusian - Native
- Russian - Native
- English - Intermediate
