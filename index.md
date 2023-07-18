```clojure
^{:nextjournal.clerk/visibility #{:hide :hide-ns}}
(ns index
  (:require [nextjournal.clerk :as clerk])
  (:import [java.net URL]
           [javax.imageio ImageIO]))
```

# 🎪 Minimal Clerk Demo

```clojure
(clerk/html
  [:p "The answer to life, the universe, and everything: " (* 23 19)])
  
```

## An image from CAS

```clojure
(ImageIO/read (URL. "https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/The_Sower.jpg/1510px-The_Sower.jpg"))
```

## More content

123
