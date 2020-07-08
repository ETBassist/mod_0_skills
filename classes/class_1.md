# class Chef

#### Chef attributes

1. chef_name (String)
1. current_tasks (Array)
1. on_duty (Boolean)
1. pay_per_hour (Float)


#### Chef methods

1. assign_task (adds string "task" to `current_task` array)
1. give_raise (adds to `pay_per_hour` float)
1. clock_in (sets `on_duty` to `true`)
1. rename (changes `chef_name`)
