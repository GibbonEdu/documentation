---
title: "CourseGateway"
weight: 0
class: \Gibbon\Domain\Timetable\CourseGateway
generated: true
---

## CourseGateway

Queryable Gateway



* Full name: \Gibbon\Domain\Timetable\CourseGateway
* Parent class: \Gibbon\Domain\QueryableGateway

{{< api-example >}} 



### Methods

- [queryCoursesBySchoolYear](#querycoursesbyschoolyear)
- [selectClassesByCourseID](#selectclassesbycourseid)
- [selectCourseEnrolmentByRollGroup](#selectcourseenrolmentbyrollgroup)




###### Inherited from TableAware
- [getTableName]({{< ref "api/Gibbon/Domain/Traits/TableAware/index.md#gettablename" >}})
- [getTableSchema]({{< ref "api/Gibbon/Domain/Traits/TableAware/index.md#gettableschema" >}})

###### Inherited from QueryableGateway
- [newQueryCriteria]({{< ref "api/Gibbon/Domain/QueryableGateway/index.md#newquerycriteria" >}})

###### Inherited from Gateway
- [__construct]({{< ref "api/Gibbon/Domain/Gateway/index.md#__construct" >}})



### queryCoursesBySchoolYear



```php
CourseGateway::queryCoursesBySchoolYear( \Gibbon\Domain\QueryCriteria $criteria, $gibbonSchoolYearID ): \Gibbon\Domain\Timetable\DataSet
```






**Return Value:**
`\Gibbon\Domain\Timetable\DataSet`  



---

### selectClassesByCourseID



```php
CourseGateway::selectClassesByCourseID( $gibbonCourseID )
```









---

### selectCourseEnrolmentByRollGroup



```php
CourseGateway::selectCourseEnrolmentByRollGroup( $gibbonRollGroupID )
```









---
