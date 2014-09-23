  $this->recordSet = array(
            array(
                'id' => 1,
                'first_name' => 'John',
                'last_name' => 'Doe'
            ),
            array(
                'id' => 2,
                'first_name' => 'Sally',
                'last_name' => 'Smith'
            ),
            array(
                'id' => 3,
                'first_name' => 'Jane',
                'last_name' => 'Jones'
            ),



array(
                'id' => 1,
                'value' => new stdClass
            ),
            array(
                'id' => 2,
                'value' => 34.2345
            ),
            array(
                'id' => 3,
                'value' => true
            ),
            array(
                'id' => 4,
                'value' => false
            ),
            array(
                'id' => 5,
                'value' => null
            ),
            array(
                'id' => 6,
                'value' => 1234
            ),
            array(
                'id' => 7,
                'value' => 'Foo'
            ),
            array(
                'id' => 8,
                'value' => $fh
            ),
        );



 $this->numericColumns = array(
            array('aaa', '111'),
            array('bbb', '222'),
            array('ccc', '333', -1 => 'ddd'),
        );

        $this->mismatchedColumns = array(
            array('a' => 'foo', 'b' => 'bar', 'e' => 'bbb'),
            array('a' => 'baz', 'c' => 'qux', 'd' => 'aaa'),
            array('a' => 'eee', 'b' => 'fff', 'e' => 'ggg'),
        ); 