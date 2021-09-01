# Jonathan Velkeneers

## Beaches

> I love being in or near **water**, especially on **warm days**. So the beach is a perfect place for me.

---

## Going to the closest beach from NWMSU

### Driving there

1. Leave the university southbound to W 1st street taking either one of:
    - N Country club road
    - N Grand ave
    - N Ray ave
    - N Munn ave
    - N Dunn street
    - N Walnut street
2. Take a left on W 1st street eastbound
    1. Drive 6 miles
3. Take a left on Liberty road
    1. Drive for 1,5 miles
4. Take a left on 245th street
    1. Drive 0,6 miles
5. Take a left on Ridge road
6. Drive until you find a parking spot
7. Park your car, you've reached Mozingo lake's beach

### What to bring

- Towel
- Swimming gear
- Drinks
- Snacks
- Sunscreen
- (Umbrella)

---

## 4 Foods and drinks to try

1. Belgian waffles: By far the best waffles anywhere in the world, usually served with ice cream of whipped cream.
2. Belgian beer: If you are of legal drinking age, going to Belgium and trying different beers is a must. There is a
   wide variety of lagers and "Trippels".
3. Belgian fries: If you live in America, you've never eater real fries in the way they're supposed to be made. Visit
   belgium and try some.
4. Water: A lot of people drink way too much soda or other drinks, just drinking water once in a while can do you some
   good.

### Where to find these items

| Food name | Where to get it | price |
| --- | --- | --- |
| Belgian waffles | Any restaurant in Belgium | 3-6 $ | 
| Belgian Beer | Any belgian store, bar, pub or even restaurant | 2-9 $ |
| Belgian fries | Any restaurant, or specialty fries restaurant | 1-4 $ |
| Water | Anywhere | 0-3 $ |

---

## Quotes

> This is where the fun begins

- _Anakin skywalker_

> Hello there!

- _Obi-Wan Kenobi_

---

## Randomized Heap Algorithm

> A randomized heap is a priority queue based data structure in which the underlying structure is also a heap-ordered binary tree. However, there are no restrictions on the shape of the underlying binary tree.

- [source](https://en.wikipedia.org/wiki/Randomized_meldable_heap)

<br>

```
Tree* merge(Tree* t1, Tree* t2) {
    if (!t1 || !t2)
        return t1 ? t1 : t2;
    if (t2->value < t1->value)
        swap(t1, t2);
    if (rand() & 1)
        swap(t1->l, t1->r);
    t1->l = merge(t1->l, t2);
    return t1;
}
```

- [source](https://cp-algorithms.com/data_structures/randomized_heap.html)

<br>

Check out my about me file [here](AboutMe.md)