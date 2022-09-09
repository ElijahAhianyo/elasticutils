# Elasticutils Utils

[_Documentation generated by Documatic_](https://www.documatic.com)

<!---Documatic-section-Codebase Structure-start--->
## Codebase Structure

<!---Documatic-block-system_architecture-start--->
```mermaid
None
```
<!---Documatic-block-system_architecture-end--->

# #
<!---Documatic-section-Codebase Structure-end--->

<!---Documatic-section-elasticutils.utils.chunked-start--->
## [elasticutils.utils.chunked](3-elasticutils_utils.md#elasticutils.utils.chunked)

<!---Documatic-section-chunked-start--->
<!---Documatic-block-elasticutils.utils.chunked-start--->
<details>
	<summary><code>elasticutils.utils.chunked</code> code snippet</summary>

```python
def chunked(iterable, n):
    iterable = iter(iterable)
    while 1:
        t = tuple(islice(iterable, n))
        if t:
            yield t
        else:
            return
```
</details>
<!---Documatic-block-elasticutils.utils.chunked-end--->
<!---Documatic-section-chunked-end--->

# #
<!---Documatic-section-elasticutils.utils.chunked-end--->

<!---Documatic-section-elasticutils.utils.to_json-start--->
## [elasticutils.utils.to_json](3-elasticutils_utils.md#elasticutils.utils.to_json)

<!---Documatic-section-to_json-start--->
<!---Documatic-block-elasticutils.utils.to_json-start--->
<details>
	<summary><code>elasticutils.utils.to_json</code> code snippet</summary>

```python
def to_json(data):
    return JSONSerializer().dumps(data)
```
</details>
<!---Documatic-block-elasticutils.utils.to_json-end--->
<!---Documatic-section-to_json-end--->

# #
<!---Documatic-section-elasticutils.utils.to_json-end--->

[_Documentation generated by Documatic_](https://www.documatic.com)