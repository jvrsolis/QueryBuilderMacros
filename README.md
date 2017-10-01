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
    Builder::removeJoinWhere - Remove a join where from the query
    Builder::removeLeftJoin - Remove a left join from the query.
    Builder::removeLeftJoinWhere - Remove a "left join where" clause from the query.
    Builder::removeRightJoin - Remove a right join from the query.
    Builder::removeRightJoinWhere - Remove a "right join where" clause to the query.
    Builder::removeCrossJoin - Remove a "cross join" clause to the query.
    Builder::diffWheres - Diff an array of where clauses and bindings.
    Builder::removeWhere - Remove a basic where clause to the query.
    Builder::removeArrayOfWheres - Remove an array of where clauses from the query.
    Builder::removeOrWhere - Remove an "or where" clause from the query.
    Builder::removeWhereColumn - Remove a "where" clause comparing two columns from the query.
    Builder::removeOrWhereColumn - Remove an "or where" clause comparing two columns from the query.
    Builder::removeWhereRaw - Remove a raw where clause from the query.
    Builder::removeOrWhereRaw - Remove a raw or where clause from the query.
    Builder::removeWhereIn - Remove a "where in" clause from the query.
    Builder::removeOrWhereIn - Remove an "or where in" clause from the query.
    Builder::removeWhereNotIn - Remove a "where not in" clause from the query.
    Builder::removeOrWhereNotIn - Remove an "or where not in" clause from the query.
    Builder::removeWhereInSub - Remove a where in with a sub-select from the query.
    Builder::removeWhereInExistingQuery - Remove an external sub-select from the query.
    Builder::removeWhereNull - Remove a "where null" clause from the query.
    Builder::removeOrWhereNull - Remove an "or where null" clause from the query.
    Builder::removeWhereNotNull - Remove a "where not null" clause from the query.
    Builder::removeWhereBetween - Remove a where between statement from the query.
    Builder::removeOrWhereBetween - Remove an or where between statement from the query.
    Builder::removeWhereNotBetween - Remove a where not between statement from the query.
    Builder::removeOrWhereNotBetween - Remove an or where not between statement from the query.
    Builder::removeOrWhereNotNull - Remove an "or where not null" clause from the query.
    Builder::removeWhereDate - Remove a "where date" statement from the query.
    Builder::removeOrWhereDate - Remove an "or where date" statement to the query.
    Builder::removeWhereTime - Remove a "where time" statement from the query.
    Builder::removeOrWhereTime - Remove an "or where time" statement from the query.
    Builder::removeWhereDay - Remove a "where day" statement from the query.
    Builder::removeWhereMonth - Remove a "where month" statement from the query.
    Builder::removeWhereYear - Remove a "where year" statement from the query.
    Builder::removeDateBasedWhere - Remove a date based (year, month, day, time) statement from the query.
    Builder::removeWhereNested - Remove a nested where statement from the query.
    Builder::removeNestedWhereQuery - Remove another query builder as a nested where from the query builder.
    Builder::removeWhereSub - Remove a full sub-select from the query.
    Builder::removeWhereExists - Remove an exists clause from the query.
    Builder::removeOrWhereExists - Remove an or exists clause from the query.
    Builder::removeWhereNotExists - Remove a where not exists clause from the query.
    Builder::removeOrWhereNotExists - Remove a where not exists clause from the query.
    Builder::removeWhereExistsQuery - Remove an exists clause from the query.
    Builder::removeDynamicWhere - Handles removal of dynamic "where" clauses from the query.
    Builder::removeDynamic - Remove a single dynamic where clause statement from the query.
    Builder::removeGroupBy - Remove a "group by" clause to the query.
    Builder::removeHaving - Remove a "having" clause from the query.
    Builder::removeOrHaving - Remove a "or having" clause from the query.
    Builder::removeHavingRaw - Remove a raw having clause from the query.
    Builder::removeOrHavingRaw - Remove a raw or having clause from the query.
    Builder::removeOrderBy - Remove an "order by" clause from the query.
    Builder::removeOrderByDesc - Remove a descending "order by" clause from the query.
    Builder::removeOldest - Remove an "order by" clause for a timestamp from the query.
    Builder::removeLatest - Remove an "order by" clause for a timestamp from the query.
    Builder::removeOrderByRaw - Remove a raw "order by" clause from the query.
    Builder::getOffset - Get the "offset" value of the query.
    Builder::removeOffset - Remove the "offset" value from the query.
    Builder::give - Give back a subset of the "limit" value from the query. Opposite of take.
    Builder::free - Free up values from a limit. Less values are limited.
    Builder::removeLimit - Remove the "limit" value from the query.
    Builder::getLimit - Get the "limit" value from the query.
    Builder::removeUnion - Remove a union statement from the query. 
    Builder::removeUnionAll - Remove a union all statement from the query.
    Builder::selectAggregate - Add a sub-select aggregate expression to the query.
    Builder::removeSelectAggregate - Remove a sub-select aggregate expression from the query.
    Builder::parseSelectAggregate - Parse the sub-select query into SQL and bindings.
    Builder::if - Add a where clause if a certain condition is met.
    Builder::last - Obtain the last item.
    Builder::orderByRandom - Create a random raw orderby
    Builder::lists - Returns an array of results containing the values of the specified column.
    Builder::firstOrFail - Find the first record or throw an exception.
    Builder::toCollection - Return a standard Collection object instead of an Eloquent Collection.
    Builder::toCollectionStrict - Transform all nested array's within the resulting collection into 
    standard collection objects.
    Builder::toArrayStrict - Return a series of arrays as the result transforms any stdClass or 
    Collection Objects into arrays including the parent wrapper.
    Builder::toGeneric - Return stdClass Objects as the result.
