Add semicolons;

Simply add a semicolon at the end of each non-blank (non-empty) line;

 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_second);
 Intent intent = getIntent();
 String text = intent.getStringExtra("text");

 TextView view = findViewById(R.id.textView2);
 view.setText(text);

:g/./ s/$/;/
