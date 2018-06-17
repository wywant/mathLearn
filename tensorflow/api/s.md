# saturate_cast(...)
Performs a safe saturating cast of value to dtype.

# scalar_mul(...)
Multiplies a scalar times a Tensor or IndexedSlices object.

# scan(...)
scan on the list of tensors unpacked from elems on dimension 0.

# scatter_add(...)
Adds sparse updates to the variable referenced by resource.

# scatter_div(...)
Divides a variable reference by sparse updates.

# scatter_max(...)
Reduces sparse updates into a variable reference using the max operation.

# scatter_min(...)
Reduces sparse updates into a variable reference using the min operation.

# scatter_mul(...)
Multiplies sparse updates into a variable reference.

# scatter_nd(...)
Scatter updates into a new (initially zero) tensor according to indices.

# scatter_nd_add(...)
Applies sparse addition between updates and individual values or slices

# scatter_nd_sub(...)
Applies sparse subtraction between updates and individual values or slices

# scatter_nd_update(...)
Applies sparse updates to individual values or slices in a Variable.

# scatter_sub(...)
Subtracts sparse updates to a variable reference.

# scatter_update(...)
Applies sparse updates to a variable reference.

# segment_max(...)
Computes the maximum along segments of a tensor.

# segment_mean(...)
Computes the mean along segments of a tensor.

# segment_min(...)
Computes the minimum along segments of a tensor.

# segment_prod(...)
Computes the product along segments of a tensor.

# segment_sum(...)
Computes the sum along segments of a tensor.

# self_adjoint_eig(...)
Computes the eigen decomposition of a batch of self-adjoint matrices.

# self_adjoint_eigvals(...)
Computes the eigenvalues of one or more self-adjoint matrices.

# sequence_mask(...)
Returns a mask tensor representing the first N positions of each cell.

# serialize_many_sparse(...)
Serialize N-minibatch SparseTensor into an [N, 3] Tensor.

# serialize_sparse(...)
Serialize a SparseTensor into a 3-vector (1-D Tensor) object.

# serialize_tensor(...)
Transforms a Tensor into a serialized TensorProto proto.

# set_random_seed(...)
Sets the graph-level random seed.

# setdiff1d(...)
Computes the difference between two lists of numbers or strings.

# shape(...)
Returns the shape of a tensor.

# shape_n(...)
Returns shape of tensors.

# sigmoid(...)
Computes sigmoid of x element-wise.

# sign(...)
Returns an element-wise indication of the sign of a number.

# sin(...)
Computes sin of x element-wise.

# sinh(...)
Computes hyperbolic sine of x element-wise.

# size(...)
Returns the size of a tensor.

# slice(...)
Extracts a slice from a tensor.

# space_to_batch(...)
SpaceToBatch for 4-D tensors of type T.

# space_to_batch_nd(...)
SpaceToBatch for N-D tensors of type T.

# space_to_depth(...)
SpaceToDepth for tensors of type T.

# sparse_add(...)
Adds two tensors, at least one of each is a SparseTensor.

# sparse_concat(...)
Concatenates a list of SparseTensor along the specified dimension.

# sparse_fill_empty_rows(...)
Fills empty rows in the input 2-D SparseTensor with a default value.

# sparse_mask(...)
Masks elements of IndexedSlices.

# sparse_matmul(...)
Multiply matrix "a" by matrix "b".

# sparse_maximum(...)
Returns the element-wise max of two SparseTensors.

# sparse_merge(...)
Combines a batch of feature ids and values into a single SparseTensor.

# sparse_minimum(...)
Returns the element-wise min of two SparseTensors.

# sparse_placeholder(...)
Inserts a placeholder for a sparse tensor that will be always fed.

# sparse_reduce_max(...)
Computes the max of elements across dimensions of a SparseTensor.

# sparse_reduce_max_sparse(...)
Computes the max of elements across dimensions of a SparseTensor.

# sparse_reduce_sum(...)
Computes the sum of elements across dimensions of a SparseTensor.

# sparse_reduce_sum_sparse(...)
Computes the sum of elements across dimensions of a SparseTensor.

# sparse_reorder(...)
Reorders a SparseTensor into the canonical, row-major ordering.

# sparse_reset_shape(...)
Resets the shape of a SparseTensor with indices and values unchanged.

# sparse_reshape(...)
Reshapes a SparseTensor to represent values in a new dense shape.

# sparse_retain(...)
Retains specified non-empty values within a SparseTensor.

# sparse_segment_mean(...)
Computes the mean along sparse segments of a tensor.

# sparse_segment_sqrt_n(...)
Computes the sum along sparse segments of a tensor divided by the sqrt(N).

# sparse_segment_sum(...)
Computes the sum along sparse segments of a tensor.

# sparse_slice(...)
Slice a SparseTensor based on the start and `size.

# sparse_softmax(...)
Applies softmax to a batched N-D SparseTensor.

# sparse_split(...)
Split a SparseTensor into num_split tensors along axis.

# sparse_tensor_dense_matmul(...)
Multiply SparseTensor (of rank 2) "A" by dense matrix "B".

# sparse_tensor_to_dense(...)
Converts a SparseTensor into a dense tensor.

# sparse_to_dense(...)
Converts a sparse representation into a dense tensor.

# sparse_to_indicator(...)
Converts a SparseTensor of ids into a dense bool indicator tensor.

# sparse_transpose(...)
Transposes a SparseTensor

# split(...): Splits a tensor into sub tensors.

# sqrt(...): Computes square root of x element-wise.

# square(...)
Computes square of x element-wise.

# squared_difference(...)
Returns (x - y)(x - y) element-wise.

# squeeze(...)
Removes dimensions of size 1 from the shape of a tensor.

# stack(...)
Stacks a list of rank-R tensors into one rank-(R+1) tensor.

# stop_gradient(...)
Stops gradient computation.

# strided_slice(...)
Extracts a strided slice of a tensor (generalized python array indexing).

# string_join(...)
Joins the strings in the given list of string tensors into one tensor;

# string_split(...)
Split elements of source based on delimiter into a SparseTensor.

# string_to_hash_bucket(...)
Converts each string in the input Tensor to its hash mod by a number of buckets.

# string_to_hash_bucket_fast(...)
Converts each string in the input Tensor to its hash mod by a number of buckets.

# string_to_hash_bucket_strong(...)
Converts each string in the input Tensor to its hash mod by a number of buckets.

# string_to_number(...)
Converts each string in the input Tensor to the specified numeric type.

# substr(...)
Return substrings from Tensor of strings.

# subtract(...)
Returns x - y element-wise.

# svd(...)
Computes the singular value decompositions of one or more matrices.
