Task 3:
    from flask_login import current_user
    if current_user == None:
        return False
    return current_user.is_authenticated

Task 4.1:
    # This code will comment out the rest of the fields (email/name/password), 
    # and then destroy the 'user' table
4.3:
    # The old code violates the security principle of Separation of Duties, where
    # the existing code is able to complete a task (and include injection) in 
    # a single line of code.

    # The new code amends the violation by parameterising the prompt from the query,
    # thus preventing the injection attack.

