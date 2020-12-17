
@@ 3,-4 +1,4 @@

'''
This function takes two arguments,
data1 and data2, which contain
@@ -50,9 +51,9 @@ def uniqueUpdate(data1, data2):
                dupKeys[k] = [v1, v2]
                # Remove (k, v1) from data1
                del data1[k]
            else:
                # Add (k, v2) to data1
                data1[k] = v2
        else:
            # Add (k, v2) to data1
            data1[k] = v2
    # After processing all (k, v2) in
    # data2, return the dictionary
    return dupKeys
