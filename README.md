Anvendelse
==========

```
./indlever -h
```

Indlevere en folder med konti-indberetninger
```
./indlever folder
```

Prøv
```
mkdir -p /tmp/sample_files/2017
echo "Invalid" > /tmp/sample_files/2017/1234-1029384756
./indlever.groovy -n --p12 ~/.oces/indberetter.p12 -c udlån -s 19552101 -p 2017 /tmp/sample_files/2017
```

REST API Dokumentation
======================

Genereret [REST API dokumentation](http://htmlpreview.github.io/?https://github.com/skat/geni-reference-groovy/blob/test-med-rest-docs/apidocs/index.html)
