# Generic

## String
The History Edition uses wide strings: wstring

The usage of most fields is
```cpp
struct wstring {
    wchar_t* text;
    int size;
    int capacity;
    int field_0C;
    int capacity_;
    int field_14;
};
```

## CList
Settlers 4 uses for lists a linked list implementation.

```cpp
template <class T>
struct CListNode {
    CListNode* next;
    CListNode* prev;
    T data;
};

template <class T>
class CList {
    CListNode<T>* start;
    int length;
};
```

!!! info
    Used in: [Config Manager](config/CConfigManager.md)


## CMap
The game uses a unordered tree structure to define dictionaries/maps

```cpp
template <class Key, class Value>
class CMap {
    CMap* left;
    CMap* right;
    CMap* parent;

    Value value;
    Key key;
    int depth;
};

template <class Key, class Value>
class CMapPair {
    Key key;
    Value value;
};
```

!!! info
    Used in: [Config Manager](config/CConfigManager.md)