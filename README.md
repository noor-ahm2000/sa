# sa
        $table->id();
                $table->string('title',100);
                $table->text('description');
                $table->enum('type', array('complaint', 'suggesion'));
                $table->string('id_stu',20);
                $table->string('name_stu',45); 
                $table->string('email_stu',45);
                $table->string('image',150);
                $table->boolean('urgent')->default(false);
