set(collections_src
    collections_module.cpp
    algorithm/collections.cpp)

mage_add_query_module(collections 1 "${collections_src}")
