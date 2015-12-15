---
---

## Hi

```python
formset = ContactFormSet(data=request.POST)
```

Factory kwargs:

- `can_delete`
- `extra`
- `max_num`

### Using Form Sets ###

```html
<form action=”” method=”POST”>
{% formset %}
</form>
```
