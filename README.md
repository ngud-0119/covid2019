![logo](./graphql.png)

# COVID-19 🦠 API<sup>:mask:</sup>  <img src="https://thumbs.gfycat.com/AjarFloweryJumpingbean-size_restricted.gif" width="60" height="60" />

### A GraphQL Express Server powered by [COVID-19 API](https://github.com/covid19india/api) to provide COVID-19 related stats for India :india:

## Queries

#### `GET` overall COVID-19 stats

```graphql
{ 
  total {
    active
    confirmed
    deaths
    recovered
  }
}
```

#### `GET` statewise COVID-19 stats

```graphql
{
  statewise {
    state
    active
    confirmed
    deaths
    recovered
  }
}
```

#### `GET` datewise COVID-19 stats

```graphql
{
  datewise {
    date
    dailyconfirmed
    dailydeceased
    dailyrecovered
  }
}

```

## Related Work

- [COVID-19 Tracker - INDIA](http://corona-cases-india.netlify.com/) - A React App with the following features:
    - Graphs showing daily **confirmed**, **recovered** and **deceased** cases
    - **State-wise** report presented in Map of India
    - Tabular data for global corona cases
    - **Latest news** about COVID-19
    - Additional resources such as symptoms, precautions etc.

- [India Fights Corona -  Get current COVID-19 stats](https://indiafightscorona.netlify.app/)!

- [COVID-19 Tracker - Homepage](https://vinitshahdeo.github.io/COVID19/)

- An [Open Letter](https://github.com/vinitshahdeo/Water-Monitoring-System/issues/236) to all the contributors -  [STAY HOME, STAY SAFE!](https://github.com/vinitshahdeo/COVID19)

## < /> with ♡ by 

[![](https://sourcerer.io/fame/vinitshahdeo/vinitshahdeo/COVID19/images/0)](https://fayz.in/stories/s/1522/0/?ckt_id=ZGL1ZGVk&title=story_of_vinit_shahdeo)[![](https://sourcerer.io/fame/vinitshahdeo/vinitshahdeo/COVID19/images/1)](https://indiafightscorona.netlify.app/)[![](https://sourcerer.io/fame/vinitshahdeo/vinitshahdeo/COVID19/images/2)](https://github.com/vinitshahdeo/COVID19)[![](https://sourcerer.io/fame/vinitshahdeo/vinitshahdeo/COVID19/images/3)](https://www.linkedin.com/in/vinitshahdeo/)[![](https://sourcerer.io/fame/vinitshahdeo/vinitshahdeo/COVID19/images/4)](http://corona-cases-india.netlify.com/)[![](https://sourcerer.io/fame/vinitshahdeo/vinitshahdeo/COVID19/images/5)](http://corona-cases-india.netlify.com/)[![](https://sourcerer.io/fame/vinitshahdeo/vinitshahdeo/COVID19/images/6)](https://github.com/vinitshahdeo)[![](https://sourcerer.io/fame/vinitshahdeo/vinitshahdeo/COVID19/images/7)](https://fayz.in/stories/s/1522/0/?ckt_id=ZGL1ZGVk&title=story_of_vinit_shahdeo)

#### [Vinit Shahdeo](https://www.eatmy.news/2020/06/code-like-you-eat-i-mean-code-daily-as.html)

## Leave a :star:

Check out **[@vinitshahdeo/COVID19](https://github.com/vinitshahdeo/COVID19)** repository. **Consider leaving a star!** :heart: :hugs:


----
```javascript

if (_.isAwesome(thisRepo)) {
  thisRepo.star(); // thanks in advance :p
}

```
----

[![GitHub followers](https://img.shields.io/github/followers/vinitshahdeo.svg?label=Follow%20@vinitshahdeo&style=social)](https://github.com/vinitshahdeo/)  [![Twitter Follow](https://img.shields.io/twitter/follow/Vinit_Shahdeo?style=social)](https://twitter.com/Vinit_Shahdeo)
