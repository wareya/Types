STL replacement header for `std::vector`, `std::shared_ptr`, `std::string`, `std::optional`, and `std::pair`. Also includes `ListMap` and `ListSet`, which wrap `Vec` and are sort of like `std::unordered_map` and `std::unordered_set`.

Not 1:1 compatible; requires some changes.

Works even with non-POD types.

API implementation is not complete; for example, `Vec` doesn't yet have an `insert_at`-esque method.
