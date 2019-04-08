# Pseudocode

It's important to show you can get your ideas out fast

Benefits
- Step-by-step
- Think About Logic
- Clarity
- Code in native language
- Help sales professionals sell the product because they really know it

Bad:
- Mixture of code and pseudocode

Pseudocode from Project
# assign the head node of the linkedlist to var current_node
# assign None to var previous_node
# assign False to var found
# while current_node is not None
    # check if the data in head is the same as the item passed in
        # then check if the node that the current_node points to is not None
            # if that prior statement is true assign the node the current_node points to the head node
            # after that set the var found to True
        # if the node that the current_node points to is None
            # then set None to the head
            # set None to the tail
            # set True to Found
            # break out of the loop

        # this time check if the data in the current_node is equal to the item passed in
            # if it is check if the current_node is equal to the tail
                # if it is set the None to the node the previous_node points to
                # set the Previous_node to the tail
                # assign True to found
                # break out of the loop
            # if the current_node is not the tail
                # set the node the current_node points to the the node that the previous_node points to
                # set True to the var Found
                # Break out of the loop
            # Otherwise
                # set current_node to previous_node
                # set the node the current_node points to to the previouus node.

Slight Improvement after feedback

# assign the head node of the linkedlist to var current_node
# assign None to var previous_node
# assign False to var found
# create loop while the head know exists
    # check if the data in head is the same as the item passed in
    # then check if the node that the current_node points to is not None
        # if that prior statement is true assign the node the current_node points to the head node
        # after that set the var found to True
    # if the node that the current_node points to is None
        # then set None to the head
        # set None to the tail
        # set True to Found
        # break out of the loop

    # this time check if the data in the current_node is equal to the item passed in
        # if it is check if the current_node is equal to the tail
            # if it is set the None to the node the previous_node points to
            # set the Previous_node to the tail
            # assign True to found
            # break out of the loop
        # if the current_node is not the tail
            # set the node the current_node points to the the node that the previous_node points to
            # set True to the var Found
            # Break out of the loop
        # Otherwise
            # set current_node to previous_node
            # set the node the current_node points to to the previouus node.
            #
