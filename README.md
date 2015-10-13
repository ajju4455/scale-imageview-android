# scale-imageview-android

About

Add pinch-in and pinch-out To Android ImageVIew.

    Double-tap to enlarge
    Can pinch to zoom in or out on the view 

<B>Example Code</B>

Are very similar to ImageView

Setting Layout XML

    <com.matabii.dev.scaleimageview.ScaleImageView
       android:id="@+id/image"
       android:layout_width="fill_parent"
       android:layout_height="fill_parent"
       android:src="@drawable/sample" />

or setImageBitmap

    ScaleImageView image = (ScaleImageView) findViewById(R.id.image);
    Bitmap bitmap = BitmapFactory.decodeStream(is);
    image.setImageBitmap(bitmap);
