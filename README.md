# sqlinlimited
Generate a sql without the 1000 limit in "IN" Parameters

1. You need to provide a list like:
```
elem773
elem774
elem775
elem776
elem777
elem778
```

2. Put the sql request into the field like:
```sql
SELECT * FROM TABLE WHERE FIELD in ( {{LISTE}} )
```

With {{LISTE}} the list you want to generate.

3. Click on generate

4. Copy and paste you generated sql on your favorite SQL IDE.