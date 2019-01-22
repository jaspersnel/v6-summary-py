|:lock: Privacy Preserving Distributed Learning (ppdDLI) |
|------------------|
| This algorithm is part of the [ppDLI](https://github.com/IKNL/ppDLI). A docker build of this algorithm can be obtained from docker-registry.distributedlearning.ai/dsummary |

# Distributed Summary
Algorithm that is inspired by the `Summary` function in R.  

## Privacy Preserving Dis

## Possible Privacy Issues

:bell: Categorial column with only one category
:bell: Outliers Min, Max are reported

```
docker run -e DATABASE_URI=/app/database.csv -v C:\Users\FMa1805.36838\Repositories\dSummary\local\input.txt:/app/input.txt -v C:\Users\FMa1805.36838\Repositories\dSummary\local\output.txt:/app/output.txt -v C:\Users\FMa1805.36838\Repositories\dSummary\local\database.csv:/app/database.csv dsummary
```
