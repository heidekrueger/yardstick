# `fn` is validated

    Code
      new_class_metric(1, "maximize")
    Condition
      Error in `new_metric()`:
      ! `fn` must be a function.

# `direction` is validated

    Code
      new_class_metric(function() 1, "min")
    Condition
      Error in `new_metric()`:
      ! `direction` must be one of "maximize", "minimize", or "zero", not "min".
      i Did you mean "minimize"?

