# QueryBuilderMacros
Useful query builder macros designed to provide extra functionality not given in the default builder object.
# Functions
    Builder::getSelect - Get the columns selected.
    Builder::removeSelectRaw - Remove a new "raw" select expression from the query.
    Builder::removeSelectSub - Remove a subselect expression to the query.
    Builder::removeSelect - Remove an old select column from the query.
    Builder::removeBinding - Remove a binding from the query.
    Builder::isDistinct - Determine if the builder is distinct.
    Builder::getFrom - Set the table which the query is targeting.
    Builder::removeJoin - Remove a join clause from the query.
    Builder::removeJoinWhere
    Builder::removeLeftJoin
    Builder::removeLeftJoinWhere
    Builder::removeRightJoin
    Builder::removeRightJoinWhere
    Builder::removeCrossJoin
    Builder::diffWheres
    Builder::removeWhere
    Builder::removeArrayOfWheres
    Builder::removeOrWhere
    Builder::removeWhereColumn
    Builder::removeOrWhereColumn
    Builder::removeWhereRaw
    Builder::removeOrWhereRaw
    Builder::removeWhereIn
    Builder::removeOrWhereIn
    Builder::removeWhereNotIn
    Builder::removeOrWhereNotIn
    Builder::removeWhereInSub
    Builder::removeWhereInExistingQuery
    Builder::removeWhereNull
    Builder::removeOrWhereNull
    Builder::removeWhereNotNull
    Builder::removeWhereBetween
    Builder::removeOrWhereBetween
    Builder::removeWhereNotBetween
    Builder::removeOrWhereNotBetween
    Builder::removeOrWhereNotNull
    Builder::removeWhereDate
    Builder::removeOrWhereDate
    Builder::removeWhereTime
    Builder::removeOrWhereTime
    Builder::removeWhereDay
    Builder::removeOrWhereDay
    Builder::removeWhereMonth
    Builder::removeWhereYear
    Builder::removeDateBasedWhere
    Builder::removeWhereNested
    Builder::removeNestedWhereQuery
    Builder::removeWhereSub
    Builder::removeWhereExists
    Builder::removeOrWhereExists
    Builder::removeWhereNotExists
    Builder::removeOrWhereNotExists
    Builder::removeWhereExistsQuery
    Builder::removeDynamicWhere
    Builder::removeDynamic
    Builder::removeGroupBy
    Builder::removeHaving
    Builder::removeOrHaving
    Builder::removeHavingRaw
    Builder::removeOrHavingRaw
    Builder::removeOrderBy
    Builder::removeOrderByDesc
    Builder::removeOldest
    Builder::removeLatest
    Builder::removeOrderByRaw
    Builder::getOffset
    Builder::removeOffset
    Builder::give
    Builder::free
    Builder::removeLimit
    Builder::getLimit
    Builder::removeUnion
    Builder::removeUnionAll
    Builder::selectAggregate
    Builder::removeSelectAggregate
    Builder::parseSelectAggregate
    Builder::if
    Builder::last
    Builder::orderByRandom
    Builder::lists
    Builder::firstOrFail
    Builder::toCollection
    Builder::toCollectionStrict
    Builder::toArrayStrict
    Builder::toGeneric
