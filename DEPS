# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b5dc38707208efae0b7a1606790ca33d237d950e',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '4446967600048557909231722d2c92212b6ca258',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '2b2e05e088841c63c0b6fd4c9fb380d8688738d3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '321692686b64873ccf4972754e36185697993e21',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'a03d2f6d5753b365d704d58161825890baad0755',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '35a851d182cdebef408493b9a82ba212d1a2629c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '315964ad5aabd5b148a484e5fbea8a365c8d1eb3',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '2fe3a7791dc9c34a581dc45522ab9b4363b4f321',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a80bafccd11d2b4e44dee21c530da49b41083682',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
