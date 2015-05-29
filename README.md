# junit-assertion-comparison
Comparison of junit assertion libraries (assertj, hamcrest, fest, truth...)



# Overview of junit assertions libraries

| Library       | Website                                            |
| ------------- | -------------------------------------------------- |
| AssertJ       | https://joel-costigliola.github.io/assertj/        |
| Fest          | https://github.com/alexruiz/fest-assert-2.x/wiki   |
| Hamcrest      | http://hamcrest.org/JavaHamcrest/                  |
| Truth         | http://google.github.io/truth/                     |

 

# Syntax & Failure messages comparison

## Simple Equals

| Library       | Syntax                                             | Failure Messages
| ------------- | -------------------------------------------------- | ---------------
| Junit         | `assertEquals(expected, actual)`                   |
| AssertJ       | `assertThat(actual).isEqualTo(expected)`           |
| Fest          | `assertThat(actual).isEqualTo(expected)`           |
| Hamcrest      | `assertThat(actual, equalTo(expected))`            |
| Truth         | `assertThat(actual).isEqualTo(expected)`           |

## TODO
TODO

# Extensibility
TODO

# Support for external libraries
TODO

# Other Pros & Cons
TODO


