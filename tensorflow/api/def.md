# decode_base64(...)
Decode web-safe base64-encoded strings.

# decode_csv(...)
Convert CSV records to tensors. Each column maps to one tensor.

# decode_json_example(...)
Convert JSON-encoded Example records to binary protocol buffer strings.

# decode_raw(...)
Reinterpret the bytes of a string as a vector of numbers.

# delete_session_tensor(...)
Delete the tensor for the given tensor handle.

# depth_to_space(...)
DepthToSpace for tensors of type T.

# dequantize(...)
Dequantize the 'input' tensor into a float Tensor.

# deserialize_many_sparse(...)
Deserialize and concatenate SparseTensors from a serialized minibatch.

# device(...)
Wrapper for Graph.device() using the default graph.

# diag(...)
Returns a diagonal tensor with a given diagonal values.

# diag_part(...)
Returns the diagonal part of the tensor.

# digamma(...)
Computes Psi, the derivative of Lgamma (the log of the absolute value of

# div(...)
Divides x / y elementwise (using Python 2 division operator semantics).

# divide(...)
Computes Python style division of x by y.

# dynamic_partition(...)
Partitions data into num_partitions tensors using indices from partitions.

# dynamic_stitch(...)
Interleave the values from the data tensors into a single tensor.

# edit_distance(...)
Computes the Levenshtein distance between sequences.

# einsum(...)
A generalized contraction between tensors of arbitrary dimension.

# enable_eager_execution(...)
Enables eager execution for the lifetime of this program.

# encode_base64(...)
Encode strings into web-safe base64 format.

# equal(...)
Returns the truth value of (x == y) element-wise.

# erf(...)
Computes the Gauss error function of x element-wise.

# erfc(...)
Computes the complementary error function of x element-wise.

# executing_eagerly(...)
Returns True if the current thread has eager execution enabled.

# exp(...)
Computes exponential of x element-wise. .

# expand_dims(...)
Inserts a dimension of 1 into a tensor's shape.

# expm1(...)
Computes exponential of x - 1 element-wise.

# extract_image_patches(...)
Extract patches from images and put them in the "depth" output dimension.

# eye(...)
Construct an identity matrix, or a batch of matrices.

# fake_quant_with_min_max_args(...)
Fake-quantize the 'inputs' tensor, type float to 'outputs' tensor of same type.

# fake_quant_with_min_max_args_gradient(...)
Compute gradients for a FakeQuantWithMinMaxArgs operation.

# fake_quant_with_min_max_vars(...)
Fake-quantize the 'inputs' tensor of type float via global float scalars min

# fake_quant_with_min_max_vars_gradient(...)
Compute gradients for a FakeQuantWithMinMaxVars operation.

# fake_quant_with_min_max_vars_per_channel(...)
Fake-quantize the 'inputs' tensor of type float and one of the shapes: [d],

# fake_quant_with_min_max_vars_per_channel_gradient(...)
Compute gradients for a FakeQuantWithMinMaxVarsPerChannel operation.

# fft(...)
Fast Fourier transform.

# fft2d(...)
2D fast Fourier transform.

# fft3d(...)
3D fast Fourier transform.

# fill(...)
Creates a tensor filled with a scalar value.

# fixed_size_partitioner(...)
Partitioner to specify a fixed number of shards along given axis.

# floor(...)
Returns element-wise largest integer not greater than x.

# floor_div(...)
Returns x // y element-wise.

# floordiv(...)
Divides x / y elementwise, rounding toward the most negative integer.

# floormod(...)
Returns element-wise remainder of division. When x < 0 xor y < 0 is

# foldl(...)
foldl on the list of tensors unpacked from elems on dimension 0.

# foldr(...)
foldr on the list of tensors unpacked from elems on dimension 0.
