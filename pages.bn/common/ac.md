# ac

> ব্যবহারকারী কতক্ষণ সংযোগিত আছেন, সেই পরিস্থিতিগুলি প্রিন্ট করুন।
> আরও তথ্য পাবেন: <https://man.openbsd.org/ac>।

- বর্তমান ব্যবহারকারী কত সময় ধরে সংযোগিত আছে, ঘণ্টায়:

`ac`

- ব্যবহারকারী কত সময় ধরে সংযোগিত আছে, এটি ঘণ্টায় প্রিন্ট করুন:

`ac -p`

- একজন বিশেষ ব্যবহারকারী কত সময় ধরে সংযোগিত আছে তা প্রিন্ট করুন:

`ac -p {{ব্যবহারকারী_নাম}}`

- একজন বিশেষ ব্যবহারকারী কত সময় ধরে সংযোগিত আছে তা প্রতি দিন ঘণ্টায় প্রিন্ট করুন (মোটও সহ):

`ac -dp {{ব্যবহারকারী_নাম}}`