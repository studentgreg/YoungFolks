# YoungFolks

A small Python script that loads the product catalog from the [Fake Store API](https://fakestoreapi.com/) and prints a summary of every item.

## What `main.py` does

`main.py` requests the full product list from `https://fakestoreapi.com/products` and treats the JSON response as the YoungFolks store catalog.

It then:

1. Prints how many products are in the store.
2. Loops over each product and prints:
   - **Title**
   - **Category**
   - **Price**
   - **Rating** (the numeric rate, not the review count)
   - **Picture** (the product image URL)

The script uses `requests` for the HTTP call and prints results to the terminal. It does not save data, filter products, or start a web server.

## Requirements

- Python 3
- The `requests` library

```bash
pip install requests
```

## Run

```bash
python main.py
or
python3 main.py
```
