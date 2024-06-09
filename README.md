# APICountries - The Free RESTful Countries Data API

#  Documentation
Welcome to the API Countries documentation. Our FREE Restfull API provides comprehensive data about countries, including names, codes, capital cities, population, regions, languages, currencies, flags, and more.

## Endpoints

### /alpha/[code]

This endpoint retrieves detailed information about a country based on its ISO 3166-1 alpha-2 or alpha-3 code, including data such as names, capital cities, population, regions, languages, currencies, flags, and more.

```bash
curl https://www.apicountries.com/alpha/IL
```
OR
```bash
curl https://www.apicountries.com/alpha/ISR
```
### /borders/[name]

This endpoint provides a list of countries that share a border with the specified country, including detailed information such as names, codes, capital cities, population, regions, languages, currencies, flags, and more.

```bash
curl https://www.apicountries.com/borders/Israel
```
### /callingcode/[code]

This endpoint retrieves detailed information about a country based on its calling code, including data such as names, capital cities, population, regions, languages, currencies, flags, and more.

```bash
curl https://www.apicountries.com/callingcode/972
```

### /countries

This endpoint retrieves a detailed list of all countries, including information such as names, codes, capital cities, population, regions, languages, currencies, flags, and more.

```bash
curl https://www.apicountries.com/countries
```

### /lang/[language]

This endpoint retrieves a list of countries where the specified language is spoken, including detailed information such as names, codes, capital cities, population, regions, languages, currencies, flags, and more.

```bash
curl https://www.apicountries.com/lang/he
```
OR 
```bash
curl https://www.apicountries.com/lang/heb
```
### /name/[name]

This endpoint retrieves detailed information about a country based on its name, including data such as names, codes, capital cities, population, regions, languages, currencies, flags, and more.

```bash
curl https://www.apicountries.com/name/Israel
```
### /region/[region]

This endpoint retrieves a list of countries in the specified region, including detailed information such as names, codes, capital cities, population, regions, languages, currencies, flags, and more.

```bash
curl https://www.apicountries.com/region/Asia
```
### /subregion/[subregion]

This endpoint retrieves a list of countries in the specified subregion, including detailed information such as names, codes, capital cities, population, regions, languages, currencies, flags, and more.

```bash
curl https://www.apicountries.com/subregion/Western%20Asia
```
## About API Countries

API Countries (apicountries.com) is a FREE Restfull comprehensive API that provides detailed data about countries across the globe. Our endpoints are designed to deliver rich information that can be used in various applications, including geography education, travel planning, demographic studies, and more.

For more information and to start using the API, visit our website at https://apicountries.com.

