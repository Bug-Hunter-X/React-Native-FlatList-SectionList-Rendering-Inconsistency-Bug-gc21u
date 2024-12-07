# React Native FlatList/SectionList Rendering Inconsistency Bug

This repository demonstrates a common bug in React Native involving FlatList and SectionList components where data inconsistencies lead to incorrect rendering. The bug arises from directly mutating the data array instead of creating a new one when updating the data source.  This results in missing, duplicated, or out of order items.

The `FlatListBug.js` file shows the buggy implementation.  `FlatListBugSolution.js` provides the corrected version, highlighting the importance of creating a new array when updating the data to ensure proper re-rendering.