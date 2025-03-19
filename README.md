Extend the Rowset class to add custom methods.

**.findEarliestChangedEffectiveDate()**
**.findLatestChangedEffectiveDate()**
These two methods will crawl through the hierarchy of a given Rowset to find which effective date, if any, has changed data.
Useful for synching data with interfaces to other systems, or tiggering processes to update data based on effective data data changes.
