x <- 1:1000
y <- atan(1/x)
print(y)
z <- 1/tan(y)
print(z)
x == z
identical(x,z)
all.equal(x,z)
true_and_missing <- TRUE
any(true_and_missing)
all(true_and_missing)
false_and_missing <- FALSE
any(false_and_missing)
all(false_and_missing)
mixed <- TRUE
any(mixed)
all(mixed)
mixed <- FALSE
any(mixed)
all(mixed)
mixed <- NA
any(mixed)
all(mixed)

class(Inf)
typeof(Inf)
mode(Inf)
storage.mode(Inf)
class(NA)
typeof(NA)
mode(NA)
storage.mode(NA)
class(NaN)
typeof(NaN)
mode(NaN)
storage.mode(NaN)
gender_char <- sample(c("dog","cat","hamster","goldfish"),1000,replace = TRUE)
as.integer(gender)
cucumber <- 1
cabbage <- "vegetable"
tomatoes <- TRUE
Is()
Is(pattern = "a")
