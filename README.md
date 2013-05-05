# NAME

Data::Sample::SQL::Slow - generate slow-query sample data

# SYNOPSIS

    use Data::Sample::SQL::Slow;
    my $slowquery = new Data::Sample::SQL::Slow;
    $slowquery->toStr();
    # =>
    # # Time: 1367780805
    # # User@Host: hoge[hoge] @ localhost []  Id: 13254
    # # Query_time: 0.1  Lock_time: 0.1 Rows_sent: 1452  Rows_examined: 1328594
    # SET timestamp=1367780805
    # SELECT * FROM blogs WHERE name LIKE "%hoge%"


# DESCRIPTION

Data::Sample::SQL::Slow is slow-query sample data generator.

# LICENSE

Copyright (C) muddydixon.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

muddydixon <muddydixon@gmail.com>
