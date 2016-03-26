# RBCallbkRecyclerView
 Add the callback of reaching bottom into RecyclerView  ; Support three LayoutManager(Linear、Grid、StaggeredGrid)

#Easy to use
##it extends RecyclerView,and you can set the reach bottom listener just like:
<code>
mRBCallbkRecyclerView.setOnReachBottomListener(new RBCallbkRecyclerView.OnReachBottomListener() {
            @Override
            public void onReachBottom() {

            }
        });
</code>

##Also, you can set the reachBottomRow(see the meaning in the code）.
<code>
mRBCallbkRecyclerView.setReachBottomRow(1);
</code>

#Not perfect 
##If you find some bug or have some idea，please commit it to "Issues",ths.
