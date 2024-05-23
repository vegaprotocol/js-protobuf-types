# Vega protobuf types

Typescript types for all Vega protobuf messages, including transactions.

```ts
export enum ConditionOperator {
  /** The default value */
  OPERATOR_UNSPECIFIED = "OPERATOR_UNSPECIFIED",
  /** Verify if the property values are strictly equal or not. */
  OPERATOR_EQUALS = "OPERATOR_EQUALS",
  /** Verify if the data source data value is greater than the Condition value. */
  OPERATOR_GREATER_THAN = "OPERATOR_GREATER_THAN",
  /** Verify if the data source data value is greater than or equal to the Condition
  value. */
  OPERATOR_GREATER_THAN_OR_EQUAL = "OPERATOR_GREATER_THAN_OR_EQUAL",
  /** Verify if the data source data value is less than the Condition value. */
  OPERATOR_LESS_THAN = "OPERATOR_LESS_THAN",
  /** Verify if the data source data value is less or equal to than the Condition
  value. */
  OPERATOR_LESS_THAN_OR_EQUAL = "OPERATOR_LESS_THAN_OR_EQUAL",
}

/** Operator describes the type of comparison.*/
export enum ConditionOperatorNumber {
  /** The default value */
  OPERATOR_UNSPECIFIED = 0,
  /** Verify if the property values are strictly equal or not. */
  OPERATOR_EQUALS = 1,
  /** Verify if the data source data value is greater than the Condition value. */
  OPERATOR_GREATER_THAN = 2,
  /** Verify if the data source data value is greater than or equal to the Condition
  value. */
  OPERATOR_GREATER_THAN_OR_EQUAL = 3,
  /** Verify if the data source data value is less than the Condition value. */
  OPERATOR_LESS_THAN = 4,
  /** Verify if the data source data value is less or equal to than the Condition
  value. */
  OPERATOR_LESS_THAN_OR_EQUAL = 5,
}
```
