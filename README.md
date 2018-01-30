# VDHRelativeLayout
一个支持指定子view拖动的RelativeLayout封装。
 
** **控件描述**：## 
 VDHRelativeLayout继承自RelativeLayout，实现了ViewDragHelper方法，支持子view拖动。也可以指定某些子view不支持拖动。
 
** ## 使用方法：**
 1、将VDHRelativeLayout.java下载，并拷贝到自己的工程项目
 2、然后就可以在布局文件中直接使用
 如：
 
     <two.isay.com.simpletext.scale.VDHRelativeLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <Button
            android:id="@+id/btn_vdl"
            android:layout_width="250dp"
            android:layout_height="50dp"
            android:text="这是一个Button"
            android:background="#50f90f" />

        <TextView
            android:id="@+id/tv_vdl"
            android:layout_width="50dp"
            android:layout_height="250dp"
            android:text="这是一个TextView"
            android:background="#f00000" />

    </two.isay.com.simpletext.scale.VDHRelativeLayout>
 
