=====
Usage
=====

To use datemore in a project:

.. code-block:: python

    import datemore.date
    sunday = datemore.date.Date(2020, 2, 2)
    tuesday = sunday.add_days(2)
    passed_days = sunday.range_to(tuesday)
    tuesday.native()  # Get the native datetime.date object

Feel free to add more usage examples!
