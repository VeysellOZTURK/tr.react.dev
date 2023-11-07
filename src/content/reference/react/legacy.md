---
title: "Eski React API'ları"
---

<Intro>

Bu API'lar `react` paketinden ihraç edilir, ancak yeni yazılan kodlarda kullanılması önerilmez. Önerilen alternatifler için her birisinde belirtilen API sayfalarına bakın.

</Intro>

---

## Eski API'lar {/*legacy-apis*/}

* [`Children`](/reference/react/Children) `children` prop'u olarak alınan JSX'i değiştirmenizi ve dönüştürmenizi sağlar. [Alternatiflere bakın.](/reference/react/Children#alternatives)
* [`cloneElement`](/reference/react/cloneElement) başka bir React elemanını kullanarak bir React elemanı oluşturmanızı sağlar. [Alternatiflere bakın.](/reference/react/cloneElement#alternatives)
* [`Component`](/reference/react/Component) bir React elemanını JavaScript sınıfı olarak tanımlamanızı sağlar. [Alternatiflere bakın.](/reference/react/Component#alternatives)
* [`createElement`](/reference/react/createElement) bir React elemanı oluşturmanızı sağlar. Genellikle bunun yerine JSX kullanırsınız.
* [`createRef`](/reference/react/createRef) herhangi bir değer tutan bir ref objesi oluşturmanızı sağlar. [Alternatiflere bakın.](/reference/react/createRef#alternatives)
* [`isValidElement`](/reference/react/isValidElement) bir değerin React elemanı olup olmadığını kontrol eder. Genellikle [`cloneElement`.](/reference/react/cloneElement) ile birlikte kullanılır.
* [`PureComponent`](/reference/react/PureComponent); [`Component`](/reference/react/Component) gibidir. Ancak aynı prop'lar olduğunda tekrar render etmeyi atlar. [Alternatiflere bakın.](/reference/react/PureComponent#alternatives)


---

## Kullanımdan Kaldırılan API'lar {/*deprecated-apis*/}

<Deprecated>

Bu API'lar React'ın gelecekteki bir ana sürümünde kaldırılacaktır.

</Deprecated>

* [`createFactory`](/reference/react/createFactory) belirli tiplerde React elemanları üreten bir fonksiyon oluşturmanızı sağlar.
